# Ashwini-Lab2
Calculator test
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
