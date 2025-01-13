package ru.netology.service;

import org.testng.annotations.Test;

public class CashbackHackServiceTest {

    @org.testng.annotations.Test
    public void value1000() {
        CashbackHackService service = new CashbackHackService();
        int amount = 0;

        int actual = service.remain(amount);
        int expected = 1000;

        org.testng.Assert.assertEquals(actual, expected);
    }

    @org.testng.annotations.Test
    public void value0() {
        CashbackHackService service = new CashbackHackService();
        int amount = 1000;

        int actual = service.remain(amount);
        int expected = 0;

        org.testng.Assert.assertEquals(actual, expected);
    }

    @org.testng.annotations.Test
    public void value100() {
        CashbackHackService service = new CashbackHackService();
        int amount = 900;

        int actual = service.remain(amount);
        int expected = 100;

        org.testng.Assert.assertEquals(actual, expected);
    }

    @org.testng.annotations.Test
    public void valueMore1000() {
        CashbackHackService service = new CashbackHackService();
        int amount = 1900;

        int actual = service.remain(amount);
        int expected = 100;

        org.testng.Assert.assertEquals(actual, expected);
    }
}
