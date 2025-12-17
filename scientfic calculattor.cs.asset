 

using System; 
using System.Collections.Generic; 
using System.ComponentModel; using System.Data;
using System.Drawing; using System.Linq; using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;
namespace scientfic_calculattor { 
    public partial class Form1 : Form { 
        double enterFirstValue, enterSecondValue;
        string op; public Form1() { InitializeComponent();
        }
        private void Form1_Load(object sender, EventArgs e)
        { this.Width = 350;//817 txtResult.Width = 296;
        }
        private void button1_Click(object sender, EventArgs e) 
        {
            enterSecondValue = Convert.ToDouble(txtResult.Text)
        
            switch (op) {
                case "+":
            
                    txtResult.Text = (enterFirstValue + enterSecondValue).ToString();
                    break;

                case "-":
                    txtResult.Text = (enterFirstValue - enterSecondValue).ToString();
                    break;

                case "*":
                    txtResult.Text = (enterFirstValue * enterSecondValue).ToString();
                    break;

                case "/":
                    if (enterSecondValue == 0)
                        txtResult.Text = "Cannot divide by zero";
                    else
                        txtResult.Text = (enterFirstValue / enterSecondValue).ToString();
                    break;


                case "Mod":
                    txtResult.Text = (enterFirstValue % enterSecondValue).ToString();
                    break;

              case "Exp":
                    double i = Convert.ToDouble(txtResult .Text);
                    double j;
                    j = enterSecondValue;

                    txtResult.Text = Math.Exp(i * Math.Log(j *4)).ToString();
                    break;


                default:
                    break;
            }
}}



        private void Enternumbers(object sender, EventArgs e)
        {
            Button num = (Button)sender;
            if (txtResult.Text == "0")
                txtResult.Text = "";
            {
                if (num.Text == ".")
                {
                    if (!txtResult.Text.Contains("."))
                        txtResult.Text = txtResult.Text + num.Text;
                }
                else
                {
                    txtResult.Text = txtResult.Text + num.Text;
                }
            }
        }}

        private void numberOper(object sender, EventArgs e)
        {
            Button num = (Button)sender;

            enterFirstValue = Convert.ToDouble(txtResult.Text);
            op = num.Text;
            txtResult.Text = "";
        }

        private void btnClear_Click(object sender, EventArgs e)
        {
            txtResult.Text = "0";
        }

        private void btnClearEntry_Click(object sender, EventArgs e)
        {
            txtResult.Text = "0";

            string f, s;

            f = Convert.ToString(enterFirstValue);
            s = Convert.ToString(enterSecondValue);

            f = "";
            s = "";

        }

        private void btnPM_Click(object sender, EventArgs e)
        {
            double q = Convert.ToDouble(txtResult.Text);
            txtResult.Text = Convert.ToString(-1 * q);
        }

        private void btnBS_Click(object sender, EventArgs e)
        {
            if (txtResult.Text.Length > 0)
            {
                txtResult.Text = txtResult.Text.Remove(txtResult.Text.Length - 1, 1);
            }


            if (txtResult.Text == "")
            {
                txtResult.Text = "0";
            }
        }

        private void standardToolStripMenuItem_Click(object sender, EventArgs e)
        {
            this.Width = 350;//817
            txtResult.Width = 296;
        }

        private void scientficToolStripMenuItem_Click(object sender, EventArgs e)
        {
            this.Width = 662;//817
            txtResult.Width = 622;
        }

        private void extToolStripMenuItem_Click(object sender, EventArgs e)
        {
            DialogResult exitCal;

            exitCal = MessageBox.Show("confirm if you want to exit", "scientfic Calculator",
                MessageBoxButtons.YesNo, MessageBoxIcon.Question);

            if (exitCal == DialogResult.Yes)
            {
                Application.Exit();
            }
        }

        private void btnPi_Click(object sender, EventArgs e)
        {
            txtResult.Text = "3.141592653589976323";
        }

        private void btnLog_Click(object sender, EventArgs e)
        {
            double logg = Convert.ToDouble(txtResult.Text);
            logg = Math.Log10(logg);
            txtResult.Text = Convert.ToString(logg);
        }

        private void btnSq_Click(object sender, EventArgs e)
        {
            double sq = Convert.ToDouble(txtResult.Text);
            sq = Math.Sqrt(sq);
            txtResult.Text = Convert.ToString(sq);
        }

        private void btnx2_Click(object sender, EventArgs e)
        {
            double x;
            x = Convert.ToDouble(txtResult.Text) * Convert.ToDouble(txtResult.Text);
            txtResult.Text = Convert.ToString(x);
        }

        private void btnx3_Click(object sender, EventArgs e)
        {
            double x,q,p,m;
          q = Convert.ToDouble(txtResult.Text) * Convert.ToDouble(txtResult.Text);
          p = Convert.ToDouble(txtResult.Text) * Convert.ToDouble(txtResult.Text);
          m = Convert.ToDouble(txtResult.Text) * Convert.ToDouble(txtResult.Text);
            x = ( q * p * m);
            txtResult.Text = Convert.ToString(x);
        }

        private void btnSinh_Click(object sender, EventArgs e)
        {
            double sh = Convert.ToDouble(txtResult.Text);
            sh = Math.Sinh(sh);
            txtResult.Text = Convert.ToString(sh);
        }

        private void btnSin_Click(object sender, EventArgs e)
        {
            double Sin = Convert.ToDouble(txtResult.Text);
            Sin = Math.Sin(Sin);
            txtResult.Text = Convert.ToString(Sin);
        }

        private void btnCosh_Click(object sender, EventArgs e)
        {
            double Cosh = Convert.ToDouble(txtResult.Text);
            Cosh = Math.Cosh(Cosh);
            txtResult.Text = Convert.ToString(Cosh);
        }

        private void btnCos_Click(object sender, EventArgs e)
        {
            double Cos = Convert.ToDouble(txtResult.Text);
            Cos = Math.Cos(Cos);
            txtResult.Text = Convert.ToString(Cos);
        }

        private void btnTanh_Click(object sender, EventArgs e)
        {
            double Tanh = Convert.ToDouble(txtResult.Text);
            Tanh = Math.Tanh(Tanh);
            txtResult.Text = Convert.ToString(Tanh);
        }

        private void btnTan_Click(object sender, EventArgs e)
        {
            double Tan = Convert.ToDouble(txtResult.Text);
            Tan = Math.Tan(Tan);
            txtResult.Text = Convert.ToString(Tan);
        }

        private void btn1x_Click(object sender, EventArgs e)
        {
            double a;
            a = Convert.ToDouble(1.0 / Convert.ToDouble(txtResult.Text));
            txtResult.Text = Convert.ToString(a);
        }

        private void btnlnx_Click(object sender, EventArgs e)
        {
            double lnx = Convert.ToDouble(txtResult.Text);
            lnx = Math.Log(lnx);
            txtResult.Text = Convert.ToString(lnx);
        }

        private void btnPrc_Click(object sender, EventArgs e)
        {

        }

        private void btnPre_Click(object sender, EventArgs e)
        {
            double a;

            a = Convert.ToDouble(txtResult.Text) / Convert.ToDouble(100);

            txtResult.Text = Convert.ToString(a);
        }

        private void btnDec_Click(object sender, EventArgs e)
        {
            double Dec = Convert.ToDouble(txtResult.Text);
            int i1 = Convert.ToInt32(Dec);
            int i2 = (int)Dec;
            txtResult.Text = Convert.ToString(i2);
        }

        private void btnBin_Click(object sender, EventArgs e)
        {
            int a = int.Parse(txtResult.Text);
            txtResult.Text = Convert.ToString(a, 2);
        }

        private void btnHex_Click(object sender, EventArgs e)
        {
            int a = int.Parse(txtResult.Text);
            txtResult.Text = Convert.ToString(a, 16);
        }
        private void btnOct_Click(object sender, EventArgs e)
        {
            int a = int.Parse(txtResult.Text);
            txtResult.Text = Convert.ToString(a, 8);
        }
    }
