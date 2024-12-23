package ru.netology.service;

import org.testng.annotations.Test;

import static org.testng.Assert.assertEquals;

public class CashbackHackServiceTest {
    @Test
    public void remainWhenLessThanBoundary() {
        CashbackHackService service = new CashbackHackService();

        int expected = 100;
        int actual = service.remain(900);

        assertEquals(actual, expected);
    }
    
    @Test
    public void remainWhenMoreThanBoundary() {
        CashbackHackService service = new CashbackHackService();

        int expected = 700;
        int actual = service.remain(1300);

        assertEquals(actual, expected);
    }
    
    @Test
    public void remainWhenCashbackEqualsBoundary() {
        CashbackHackService service = new CashbackHackService();

        int expected = 0;
        int actual = service.remain(1000);

        assertEquals(actual, expected);
    }
}
