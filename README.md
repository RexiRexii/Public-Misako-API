## What is Misako API?

Misako API, is the ultimate companion to your beautiful custom UI, made so you don't have to do extra coding when using Misako's DLL.

## Installation

I will put a video here when we release it

## Usage

```cs
using System.Windows.Forms;
using MisakoApi;

namespace MisakoAPIForms
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
            Misako.Start(); // This initializes the API. Without this; you cannot use Misako API.
        }

        /// <summary>
        /// This function is used to execute whatever you put in the textbox. It will execute the given string, which can be something like a richTextBox, for example you'd put Misako.Execute(RichTextBox1.Text);
        /// </summary>
        private void button1_Click(object sender, EventArgs e)
        {
            Misako.Execute(richTextBox1.Text);
        }

        /// <summary>
        /// This will inject Misako API to ROBLOX. So you can execute scripts.
        /// </summary>
        private void button2_Click(object sender, EventArgs e)
        {
            Misako.Inject();
        }
    }
}

```

## Contributing
You can contribute to Misako API by making / releasing nice UI's and using Misako API while doing so! That would make me feel happy.

## Credits

Thanks to Rakion99
Thanks to gogo1000, iivillian, Static (Celery), Rainers, MisterGunXD, MCgamin1738, chr1s, Hiro, ImmuneLion and everyone else that I forgot (but still helped me)
also if you want me to add you to credits just tell me smhsmh (if you partook in the development of Misako)
