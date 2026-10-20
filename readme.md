# Wrap the chat functionality in a class based on C# Winform and call the DeepSeekv3 interface.

Call code:

-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-

```
using System;using System.Collections.Generic;using System.ComponentModel;using System.Data;using System.Drawing;using System.Linq;using System.Text;using System.Threading.Tasks;using System.Windows.Forms;
namespace FIRC{    public partial class Form1 : Form    {        DeepseekManager dm = null;        public Form1()        {            InitializeComponent();        }
private void button1_Click(object sender, EventArgs e)
        }
        private void Form1_Load(object sender, EventArgs e)        {            dm = new DeepseekManager("sk-1872c9e72ecexxxxxx45fbb4590a008");        }
        private void button2_Click(object sender, EventArgs e)        {            tb_res.Clear();        }    }}

```

Video demonstration: www.bilibili.com/video/BV1zNrBYEEXR/

Complete Source Code:


## Payment

Here is a pay link on Stripe ( https://buy.stripe.com/3cs8yP7sY87d0vu9AB ). Please contact me lonlonago@foxmail.com after funding $89, and I will send you a complete data files , thank you!

![111.png](111.png)
