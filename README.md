# Ashwini-Lab2
Calculator test
[Test]
        public void GetSubtraction_Input18point0and13point4_Returns4point6()
        {

            //Arrange
            double number1 = 18.0;
            double number2 = 13.4;

            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input2point6and1point1_Returns1point5()
        {

            //Arrange
            double number1 = 2.6;
            double number2 = 1.1;
            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input9point0and1point0_Returns8point0()
        {

            //Arrange
            double number1 = 9.0;
            double number2 = 1.0;
            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
