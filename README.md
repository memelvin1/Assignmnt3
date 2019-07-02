using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using AwesomeCalculator;
using NUnit.Framework;


namespace CalcAppTest

{
    [TestFixture]
    class CalcTests
    {
        [Test]
        public void GetAddition_Input3point4and5point6_Returns9point0()
        {

            //Arrange
            double number1 = 3.4;
            double number2 = 5.6;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetAddition_Input11point4and15point6_Returns24point0()
        {

            //Arrange
            double number1 = 11.4;
            double number2 = 15.6;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }


        [Test]
        public void GetAddition_Input23point6and25point6_Returns49point2()
        {

            //Arrange
            double number1 = 23.6;
            double number2 = 25.6;

            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input10point3and2point3_Returns8point0()
        {

            //Arrange
            double number1 = 10.3;
            double number2 = 2.3;

            double expextedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expextedResult, actualResult);

        }



        [Test]
        public void GetSubtraction_Input30point3and20point3_Returns10point0()
        {

            //Arrange
            double number1 = 30.3;
            double number2 = 20.3;

            double expextedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expextedResult, actualResult);

        }



        [Test]
        public void GetSubtraction_Input40point8and20point7_Returns20point1()
        {

            //Arrange
            double number1 = 10.3;
            double number2 = 2.3;

            double expextedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expextedResult, actualResult);

        }


        [Test]
        public void GetMultiplication_Input4point2and3point3_Returns13point86()
        {

            //Arrange
            double number1 = 4.2;
            double number2 = 3.3;

            double expectedResult = number1*number2 ;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

       
        }



        [Test]
        public void GetMultiplication_Input12point2and3point3_Returns40point26()
        {

            //Arrange
            double number1 = 12.2;
            double number2 = 3.3;

            double expectedResult = number1*number2 ;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);


        }

        [Test]
        public void GetMultiplication_Input8point2and9point3_Returns76point26()
        {

            //Arrange
            double number1 = 8.2;
            double number2 = 9.3;

            double expectedResult = number1*number2 ;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);


        }

        [Test]
        public void GetDivision_Input8point6and4point3_Returns2point0()
        {
            //Arrange

            double number1 = 8.6;
            double number2 = 4.3;

            double expectedResult = number1/number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetDivision_Input18point6and4point0_Returns4point65()
        {
            //Arrange

            double number1 = 18.6;
            double number2 = 4.0;

            double expectedResult = number1/number2 ;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input80point5and25point0_Returns3point22()
        {
            //Arrange

            double number1 = 80.5;
            double number2 = 25.0;

            double expectedResult = number1/number2 ;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetDivision();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
       
       
      
    }
}
