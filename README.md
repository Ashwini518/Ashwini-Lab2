       public void GetDivision_Input2point3and1point0_Returns2point3()
        {

            //Arrange
            double number1 = 2.3;
            double number2 = 1.0;
            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input3point0and1point0_Returns3point0()
        {

            //Arrange
            double number1 = 3.0;
            double number2 = 1.0;
            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input5point0and1point0_Returns5point0()
        {

            //Arrange
            double number1 = 5.0;
            double number2 = 1.0;
            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }# Ashwini-Lab2
Calculator test
