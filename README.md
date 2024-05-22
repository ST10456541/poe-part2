/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/UnitTests/EmptyTestNGTest.java to edit this template
 */
package motaungpart2.prj;

import java.util.ArrayList;
import static org.testng.Assert.*;
import org.testng.annotations.AfterClass;
import org.testng.annotations.AfterMethod;
import org.testng.annotations.BeforeClass;
import org.testng.annotations.BeforeMethod;
import org.testng.annotations.Test;

/**
 *
 * @author RC_Student_lab
 */
public class TaskNGTest {
    
    public TaskNGTest() {
    }

    @BeforeClass
    public static void setUpClass() throws Exception {
    }

    @AfterClass
    public static void tearDownClass() throws Exception {
    }

    @BeforeMethod
    public void setUpMethod() throws Exception {
    }

    @AfterMethod
    public void tearDownMethod() throws Exception {
    }

    /**
     * Test of getTaskID method, of class Task.
     */
    @Test
    public void testGetTaskID() {
        System.out.println("getTaskID");
        Task instance = new Task();
        String expResult = "";
        String result = instance.getTaskID();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setTaskID method, of class Task.
     */
    @Test
    public void testSetTaskID() {
        System.out.println("setTaskID");
        String taskID = "";
        Task instance = new Task();
        instance.setTaskID(taskID);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getName method, of class Task.
     */
    @Test
    public void testGetName() {
        System.out.println("getName");
        Task instance = new Task();
        String expResult = "";
        String result = instance.getName();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setName method, of class Task.
     */
    @Test
    public void testSetName() {
        System.out.println("setName");
        String name = "";
        Task instance = new Task();
        instance.setName(name);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getStatus method, of class Task.
     */
    @Test
    public void testGetStatus() {
        System.out.println("getStatus");
        Task instance = new Task();
        String expResult = "";
        String result = instance.getStatus();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setStatus method, of class Task.
     */
    @Test
    public void testSetStatus() {
        System.out.println("setStatus");
        String status = "";
        Task instance = new Task();
        instance.setStatus(status);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getNumber method, of class Task.
     */
    @Test
    public void testGetNumber() {
        System.out.println("getNumber");
        Task instance = new Task();
        double expResult = 0.0;
        double result = instance.getNumber();
        assertEquals(result, expResult, 0.0);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setNumber method, of class Task.
     */
    @Test
    public void testSetNumber() {
        System.out.println("setNumber");
        double number = 0.0;
        Task instance = new Task();
        instance.setNumber(number);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getTaskduration method, of class Task.
     */
    @Test
    public void testGetTaskduration() {
        System.out.println("getTaskduration");
        Task instance = new Task();
        int expResult = 0;
        int result = instance.getTaskduration();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setTaskduration method, of class Task.
     */
    @Test
    public void testSetTaskduration() {
        System.out.println("setTaskduration");
        int taskduration = 0;
        Task instance = new Task();
        instance.setTaskduration(taskduration);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getDescription method, of class Task.
     */
    @Test
    public void testGetDescription() {
        System.out.println("getDescription");
        Task instance = new Task();
        String expResult = "";
        String result = instance.getDescription();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setDescription method, of class Task.
     */
    @Test
    public void testSetDescription() {
        System.out.println("setDescription");
        String Description = "";
        Task instance = new Task();
        instance.setDescription(Description);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getDeveloper method, of class Task.
     */
    @Test
    public void testGetDeveloper() {
        System.out.println("getDeveloper");
        Task instance = new Task();
        String expResult = "";
        String result = instance.getDeveloper();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setDeveloper method, of class Task.
     */
    @Test
    public void testSetDeveloper() {
        System.out.println("setDeveloper");
        String developer = "";
        Task instance = new Task();
        instance.setDeveloper(developer);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getOption method, of class Task.
     */
    @Test
    public void testGetOption() {
        System.out.println("getOption");
        Task instance = new Task();
        int expResult = 0;
        int result = instance.getOption();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setOption method, of class Task.
     */
    @Test
    public void testSetOption() {
        System.out.println("setOption");
        int option = 0;
        Task instance = new Task();
        instance.setOption(option);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getTasks method, of class Task.
     */
    @Test
    public void testGetTasks() {
        System.out.println("getTasks");
        Task instance = new Task();
        int expResult = 0;
        int result = instance.getTasks();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setTasks method, of class Task.
     */
    @Test
    public void testSetTasks() {
        System.out.println("setTasks");
        int tasks = 0;
        Task instance = new Task();
        instance.setTasks(tasks);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getStatusOption method, of class Task.
     */
    @Test
    public void testGetStatusOption() {
        System.out.println("getStatusOption");
        Task instance = new Task();
        int expResult = 0;
        int result = instance.getStatusOption();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setStatusOption method, of class Task.
     */
    @Test
    public void testSetStatusOption() {
        System.out.println("setStatusOption");
        int statusOption = 0;
        Task instance = new Task();
        instance.setStatusOption(statusOption);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of getAccumulated method, of class Task.
     */
    @Test
    public void testGetAccumulated() {
        System.out.println("getAccumulated");
        Task instance = new Task();
        int expResult = 0;
        int result = instance.getAccumulated();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of setAccumulated method, of class Task.
     */
    @Test
    public void testSetAccumulated() {
        System.out.println("setAccumulated");
        int accumulated = 0;
        Task instance = new Task();
        instance.setAccumulated(accumulated);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of exploreTasks method, of class Task.
     */
    @Test
    public void testExploreTasks() {
        System.out.println("exploreTasks");
        ArrayList<Task> tasks = null;
        Task instance = new Task();
        boolean expResult = false;
        boolean result = instance.exploreTasks(tasks);
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of CaptureTasks method, of class Task.
     */
    @Test
    public void testCaptureTasks() {
        System.out.println("CaptureTasks");
        Task instance = new Task();
        instance.CaptureTasks();
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of CaptureTask method, of class Task.
     */
    @Test
    public void testCaptureTask() {
        System.out.println("CaptureTask");
        Task instance = new Task();
        instance.CaptureTask();
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of choosestatus method, of class Task.
     */
    @Test
    public void testChoosestatus() {
        System.out.println("choosestatus");
        Task instance = new Task();
        instance.choosestatus();
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of chooseDescription method, of class Task.
     */
    @Test
    public void testChooseDescription() {
        System.out.println("chooseDescription");
        Task instance = new Task();
        instance.chooseDescription();
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of updateProduct method, of class Task.
     */
    @Test
    public void testUpdateProduct() {
        System.out.println("updateProduct");
        ArrayList<Task> tasks = null;
        Task instance = new Task();
        instance.updateProduct(tasks);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of removeTasks method, of class Task.
     */
    @Test
    public void testRemoveTasks() {
        System.out.println("removeTasks");
        ArrayList<Task> tasks = null;
        Task instance = new Task();
        instance.removeTasks(tasks);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of updateTasks method, of class Task.
     */
    @Test
    public void testUpdateTasks() {
        System.out.println("updateTasks");
        ArrayList<Task> tasks = null;
        Task instance = new Task();
        instance.updateTasks(tasks);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of removetask method, of class Task.
     */
    @Test
    public void testRemovetask() {
        System.out.println("removetask");
        ArrayList<Task> tasks = null;
        Task instance = new Task();
        instance.removetask(tasks);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of savetask method, of class Task.
     */
    @Test
    public void testSavetask() {
        System.out.println("savetask");
        Task task = null;
        ArrayList<Task> tasks = null;
        Task instance = new Task();
        instance.savetask(task, tasks);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of display method, of class Task.
     */
    @Test
    public void testDisplay() {
        System.out.println("display");
        ArrayList<Task> tasks = null;
        Task instance = new Task();
        instance.display(tasks);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of TaskID method, of class Task.
     */
    @Test
    public void testTaskID() {
        System.out.println("TaskID");
        Task instance = new Task();
        String expResult = "";
        String result = instance.TaskID();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of TaskDetails method, of class Task.
     */
    @Test
    public void testTaskDetails() {
        System.out.println("TaskDetails");
        Task instance = new Task();
        String expResult = "";
        String result = instance.TaskDetails();
        assertEquals(result, expResult);
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }

    /**
     * Test of exitapplication method, of class Task.
     */
    @Test
    public void testExitapplication() {
        System.out.println("exitapplication");
        Task instance = new Task();
        instance.exitapplication();
        // TODO review the generated test code and remove the default call to fail.
        fail("The test case is a prototype.");
    }
    
}
