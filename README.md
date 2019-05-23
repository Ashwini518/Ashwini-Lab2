public void GetMultiplication_Input10point0and1point0_Returns10point0()
        {

            //Arrange
            double number1 = 10.0;
            double number2 = 1.0;
            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input22point0and22point0_Returns484point0()
        {

            //Arrange
            double number1 = 22.0;
            double number2 = 22.0;
            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input10point10and2point10_Returns21point21()
        {

            //Arrange
            double number1 = 10.10;
            double number2 = 2.10;
            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult# Ashwini-Lab2
Calculator test
