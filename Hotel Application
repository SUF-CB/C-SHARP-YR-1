using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;
// Name of program- Hotel Application  
// programmer-Sufyaan Shaikh 
// version 1.0
// Date Created- 17/03/2019
 

namespace HOTEL_APP
{
    public partial class Form1 : Form
    {
        int Hotel1 = 0;
        int Hotel2 = 0;
        int Hotel3 = 0;
        int Rental1 = 0;
        int Tour1 = 0;
        int Balcony1 = 0;
        int People = 1;
        int Days = 1;
        double Hotel1Price = 49.00;// hotel price 
        double Hotel2Price = 69.00; // hotel price 
        double Hotel3Price = 90.00; // hotel price 
        double RentalPrice = 250.00;// option price 
        double TourPrice = 100.00; //option price
        double BalconyPrice = 90.00;// option price 
        double TotalPrice;
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {
             TotalPrice = 0.00;
            label7.Text = "";
            label12.Text = "1 People";
            label16.Text = "1 Days";
            label8.Text = "";
            label9.Text = "None";
            label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
        }

        private void label4_Click(object sender, EventArgs e)
        {

        }

        private void pictureBox1_Click(object sender, EventArgs e)
        {

        }

        private void pictureBox2_Click(object sender, EventArgs e)
        {

        }

        private void pictureBox3_Click(object sender, EventArgs e)
        {

        }

        private void label1_Click(object sender, EventArgs e)
        {

        }

        private void label2_Click(object sender, EventArgs e)
        {

        }

        private void label3_Click(object sender, EventArgs e)
        {

        }

        private void label10_Click(object sender, EventArgs e)
        {

        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {
            label7.Text = textBox1.Text;
        }

        private void label13_Click(object sender, EventArgs e)
        {

        }

        private void numericUpDown1_ValueChanged(object sender, EventArgs e)
        {
            People = Convert.ToInt32(numericUpDown1.Value);
            label12.Text = Convert.ToString(numericUpDown1.Value) + " People"; // when the users wants to change the value of days it moves it up and down depending on thr users choice 
        }

        private void label14_Click(object sender, EventArgs e)
        {

        }

        private void numericUpDown2_ValueChanged(object sender, EventArgs e)
        {
            Days = Convert.ToInt32(numericUpDown1.Value);
            label16.Text = Convert.ToString(numericUpDown2.Value) + " Days";
        }

        private void radioButton1_CheckedChanged(object sender, EventArgs e)
        {

            // Hotel Miramar //

            if (radioButton1.Checked == true)
            {
                radioButton2.Checked = false;
                radioButton3.Checked = false;
                Hotel1 = 1;
                Hotel2 = 0;
                Hotel3 = 0;
                label8.Text = "Hotel Miramar";
            }
        }

        private void radioButton2_CheckedChanged(object sender, EventArgs e)
        {

            // Las Jazminas //

            if (radioButton2.Checked == true)
            {
                radioButton1.Checked = false;
                radioButton3.Checked = false;
                Hotel1 = 0;
                Hotel2 = 1;
                Hotel3 = 0;
                label8.Text = "Las Jazminas";
            }
        }

        private void radioButton3_CheckedChanged(object sender, EventArgs e)
        {

            // Tropicana Gardens //

            if (radioButton3.Checked == true)
            {
                radioButton1.Checked = false;
                radioButton2.Checked = false;
                Hotel1 = 0;
                Hotel2 = 0;
                Hotel3 = 1;
                label8.Text = "Tropicana Gardens";
            }
        }

        private void checkBox1_CheckedChanged(object sender, EventArgs e)
        {

            // Rental Car //
            if (checkBox1.Checked == true && checkBox2.Checked == true && checkBox3.Checked == true)
            {
                label9.Text = "Rental Car, Tours and Balcony";
                Rental1 = 1;
                Tour1 = 1;
                Balcony1 = 1;
            }
            else if (checkBox1.Checked == true && checkBox2.Checked == true)
            {
                label9.Text = "Rental Car and Tours";
                Rental1 = 1;
                Tour1 = 1;
                Balcony1 = 0;
            }
            else if (checkBox1.Checked == true && checkBox3.Checked == true)
            {
                label9.Text = "Rental Car and Balcony";
                Rental1 = 1;
                Tour1 = 0;
                Balcony1 = 1;
            }
            else if (checkBox1.Checked == true)
            {
                label9.Text = "Rental Car";
                Rental1 = 1;
                Tour1 = 0;
                Balcony1 = 0;
            }
        }

        private void checkBox2_CheckedChanged(object sender, EventArgs e)
        {
            // Tours //
            if (checkBox1.Checked == true && checkBox2.Checked == true && checkBox3.Checked == true)
            {
                label9.Text = "Rental Car, Tours and Balcony";
                Rental1 = 1;
                Tour1 = 1;
                Balcony1 = 1;
            }
            else if (checkBox1.Checked == true && checkBox2.Checked == true)
            {
                label9.Text = "Rental Car and Tours";
                Rental1 = 1;
                Tour1 = 1;
                Balcony1 = 0;
            }
            else if (checkBox2.Checked == true && checkBox3.Checked == true)
            {
                label9.Text = "Tours and Balcony";
                Rental1 = 0;
                Tour1 = 1;
                Balcony1 = 1;
            }
            else if (checkBox2.Checked == true)
            {
                label9.Text = "Tours";
                Rental1 = 0;
                Tour1 = 1;
                Balcony1 = 0;
            }
        }

        private void checkBox3_CheckedChanged(object sender, EventArgs e)
        {
            // Balcony //
            if (checkBox1.Checked == true && checkBox2.Checked == true && checkBox3.Checked == true)
            {
                label9.Text = "Rental Car, Tours and Balcony";
                Rental1 = 1;
                Tour1 = 1;
                Balcony1 = 1;
            }
            else if (checkBox3.Checked == true && checkBox2.Checked == true)
            {
                label9.Text = "Tours and Balcony";
                Rental1 = 0;
                Tour1 = 1;
                Balcony1 = 1;
            }
            else if (checkBox1.Checked == true && checkBox3.Checked == true)
            {
                label9.Text = "Rental Car and Balcony";
                Rental1 = 1;
                Tour1 = 0;
                Balcony1 = 1;
            }
            else if (checkBox3.Checked == true)
            {
                label9.Text = "Balcony";
                Rental1 = 0;
                Tour1 = 0;
                Balcony1 = 1;
            }
        }

        private void button1_Click(object sender, EventArgs e)
        {
            // SUBMIT BUTTON //

            if (checkBox1.Checked == false && checkBox2.Checked == false && checkBox3.Checked == false)
            {
                label9.Text = "None";
                Rental1 = 0;
                Tour1 = 0;
                Balcony1 = 0;
            }
            else if (checkBox3.Checked == false && checkBox2.Checked == false)
            {
                label9.Text = "Rental";
                Rental1 = 1;
                Tour1 = 0;
                Balcony1 = 0;
            }
            else if (checkBox1.Checked == false && checkBox2.Checked == false)
            {
                label9.Text = "Balcony";
                Rental1 = 0;
                Tour1 = 0;
                Balcony1 = 1;
            }
            else if (checkBox1.Checked == false && checkBox3.Checked == false)
            {
                label9.Text = "Tours";
                Rental1 = 0;
                Tour1 = 1;
                Balcony1 = 0;
            }
            else if (checkBox3.Checked == false)
            {
                label9.Text = "Rental and Tours";
                Rental1 = 1;
                Tour1 = 1;
                Balcony1 = 0;
            }
            else if (checkBox2.Checked == false)
            {
                label9.Text = "Rental and Balcony";
                Rental1 = 1;
                Tour1 = 0;
                Balcony1 = 1;
            }
            else if (checkBox1.Checked == false)
            {
                label9.Text = "Tours and Balcony";
                Rental1 = 0;
                Tour1 = 1;
                Balcony1 = 1;
            }

            if (Hotel1 == 1)
            {

                if (Rental1 == 1 && Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1 && Tour1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + RentalPrice + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + RentalPrice + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Balcony1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }

            }

            if (Hotel2 == 1)
            {

                if (Rental1 == 1 && Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1 && Tour1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + RentalPrice + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + RentalPrice + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Balcony1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }

            }

            if (Hotel3 == 1)
            {

                if (Rental1 == 1 && Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1 && Tour1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + RentalPrice + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + RentalPrice + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Balcony1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }

            }

            if (radioButton1.Checked == false && radioButton2.Checked == false && radioButton3.Checked == false) // checks if you have hotel name 
            {
                MessageBox.Show("ERROR: INVALID HOTEL");
            }
            else if (textBox1.Text == "")
            {
                MessageBox.Show("ERROR: INVALID NAME");
            }
            else
            {
                MessageBox.Show("Your Hotel Application has been submitted! \n\n This is your booking! \n\nName: " + label7.Text + " \nNo. of People: " + label12.Text + " \nDays: " + label16.Text + " \nHotel: " + label8.Text + " \nOptions: " + label9.Text + "\nTotal Price: " + String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice));
            }


        }
        private void label7_Click(object sender, EventArgs e)
        {

        }

        private void label11_Click(object sender, EventArgs e)
        {

        }

        private void label12_Click(object sender, EventArgs e)
        {

        }

        private void label15_Click(object sender, EventArgs e)
        {

        }

        private void label16_Click(object sender, EventArgs e)
        {

        }

        private void label5_Click(object sender, EventArgs e)
        {

        }

        private void label8_Click(object sender, EventArgs e)
        {

        }

        private void label6_Click(object sender, EventArgs e)
        {

        }

        private void label9_Click(object sender, EventArgs e)
        {

        }

        private void label17_Click(object sender, EventArgs e)
        {

        }

        private void label20_Click(object sender, EventArgs e)
        {

        }

        private void label19_Click(object sender, EventArgs e)
        {

        }

        private void label21_Click(object sender, EventArgs e)
        {

        }

        private void label22_Click(object sender, EventArgs e)
        {

        }

        private void label18_Click(object sender, EventArgs e)
        {

        }

        private void RentalCar(object sender, EventArgs e)
        {
            // RENTAL MOUSE HOVER // the information indented below will appear in the help box 
            label17.Text = "This option is a Rental Car which will drop you to the airport and will have to be returned back.\n\nThe cost for the Rental Car is £250.00 Per Booking.";
        }

        private void Tours(object sender, EventArgs e)
        {
            // TOUR MOUSE HOVER // the information indented below will appear in the help box 

            label17.Text = "The Tour option is a tour around local places of interest.\n\nThe cost for a tour is 100.00 Per Person.";
        }

        private void Balcony(object sender, EventArgs e)
        {
            // BALCONY MOUSE HOVER // the information indented below will appear in the help box 

            label17.Text = "The Balcony option is to get a room with a balcony to enjoy the view and smell the fresh air.\n\nThe cost for this option is £90.00 Per Booking.";
        }

        private void NAME(object sender, EventArgs e)
        {
            // NAME MOUSE HOVER // the information indented below will appear in the help box 

            label17.Text = "The person's name that is booking the hotel has to be typed into the textbox on the right";
        }

        private void PEOPLE_COUNT(object sender, EventArgs e)
        {
            // PEOPLE MOUSE HOVER // the information indented below will appear in the help box 

            label17.Text = "The amount of people staying in the hotel.\n\nNOTE: The max amount of people you are allowed to book is 50 People";
        }

        private void DAY_COUNT(object sender, EventArgs e)
        {
            // DAYS MOUSE HOVER // the information indented below will appear in the help box 

            label17.Text = "The number of days you would like to stay for.\n\nNOTE: The maximum number of days you can stay for is 7 days!";
        }

        private void TOTAL_PRICE(object sender, EventArgs e)
        {
            
        }

        private void button2_Click(object sender, EventArgs e)
        {

            // CALCULATE BUTTON //

            if (checkBox1.Checked == false && checkBox2.Checked == false && checkBox3.Checked == false)//
            {
                label9.Text = "None";
                Rental1 = 0;
                Tour1 = 0;
                Balcony1 = 0;
            }
            else if (checkBox3.Checked == false && checkBox2.Checked == false)
            {
                label9.Text = "Rental";
                Rental1 = 1;
                Tour1 = 0;
                Balcony1 = 0;
            }
            else if (checkBox1.Checked == false && checkBox2.Checked == false)
            {
                label9.Text = "Balcony";
                Rental1 = 0;
                Tour1 = 0;
                Balcony1 = 1;
            }
            else if (checkBox1.Checked == false && checkBox3.Checked == false) // checks if you have cheated the system 
            {
                label9.Text = "Tours";
                Rental1 = 0;
                Tour1 = 1;
                Balcony1 = 0;
            }
            else if (checkBox3.Checked == false)
            {
                label9.Text = "Rental and Tours";
                Rental1 = 1;
                Tour1 = 1;
                Balcony1 = 0;
            }
            else if (checkBox2.Checked == false)
            {
                label9.Text = "Rental and Balcony";
                Rental1 = 1;
                Tour1 = 0;
                Balcony1 = 1;
            }
            else if (checkBox1.Checked == false)
            {
                label9.Text = "Tours and Balcony";
                Rental1 = 0;
                Tour1 = 1;
                Balcony1 = 1;
            }

            if (Hotel1 == 1)
            {

                if (Rental1 == 1 && Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);  // coverts to british pound 
                }
            }
                else if (Rental1 == 1 && Tour1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + RentalPrice + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice); 
                }
                else if (Rental1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + RentalPrice + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Balcony1 == 1)
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else
                {
                    TotalPrice = (Hotel1Price * People) + (Days * 7);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }

            }

            if (Hotel2 == 1)
            {

                if (Rental1 == 1 && Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice); // coverts to british pound 
                }
                else if (Rental1 == 1 && Tour1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + RentalPrice + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + RentalPrice + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Balcony1 == 1)
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else
                {
                    TotalPrice = (Hotel2Price * People) + (Days * 7);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }

            }

            if (Hotel3 == 1)
            {

                if (Rental1 == 1 && Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1 && Tour1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + RentalPrice + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + RentalPrice + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1 && Balcony1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + (TourPrice * People) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Rental1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + RentalPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Tour1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + (TourPrice * People);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else if (Balcony1 == 1)
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7) + BalconyPrice;
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }
                else
                {
                    TotalPrice = (Hotel3Price * People) + (Days * 7);
                    label22.Text = String.Format(System.Globalization.CultureInfo.GetCultureInfo("en-GB"), "{0:C}", TotalPrice);
                }

            }


        }
    }
}
