---
sidebar_position: 1
---

# SQL Clock In  

:::info
To setup Time Attendance QR Code, may refer to [Time Attendance Payroll Setup](hrms/e-tms/payroll-setup.md)
:::

## Login

### Login

:::info[IMPORTANT]
Only **Managers** are able to log into this app
:::

**Step 1:** Enter email | Next  

    <!-- ![login1](../../static/img/integration/clock-in/login1.png) -->  

**Step 2:** Enter OTP sent to your email | Login  

    <!-- ![login2](../../static/img/integration/clock-in/login2.png) -->  

**Step 3:** Select a company and branch  

    <!-- ![login3](../../static/img/integration/clock-in/login3.png) -->

### Try Live Demo  

User may try out the app as manager  

**Step 1:** Try Live Demo  

    <!-- ![try-live-demo1](../../static/img/integration/clock-in/try-live-demo1.png) -->

**Step 2:** Testing Company (Demo Data) | Select a Branch  

    <!-- ![try-live-demo2](../../static/img/integration/clock-in/try-live-demo2.png) -->

    - **Logout icon (top right):** Logout from SQL Clock In app  

## Permission  

### Camera  

**From SQL Clock In app**  

**Step:** Select ***'While using the app'***  

    <!-- ![permission1](../../static/img/integration/clock-in/permission1.png) -->

**From Device Settings**  

**Step:** App Info | App permissions | Camera  

    ![permission2](../../static/img/integration/clock-in/permission2.png)

## Dashboard  

    <!-- ![dashboard](../../static/img/integration/clock-in/dashboard.png) -->

    - ***'Clock In / Out'* button:** Navigate to [QR Scanner](#qr-scanner) 
    - **Gear icon (top right):** Navigate to [Settings](#settings)   
    - **Logout icon (top right):** Logout from SQL Clock In app  

## QR Scanner  

For employees to scan the QR Code generated from SQL HRMS app to clock in / out  

    <!-- ![qr-scanner](../../static/img/integration/clock-in/qr-scanner.png) -->

    - The scanner will enter a black screen after 3 minutes of inactivity  
      - It will be wake when there's motion detected  
      - The sensitivity can be adjusted in the [settings](#settings)
  
| **Dialog Message** | **Explanation** |  
| :----------------- | :-------------- |  
| <!-- ![dialog1](../../static/img/integration/clock-in/dialog1.png) --> | Employee scanned an invalid QR Code that is not generated from SQL HRMS app |  
| <!-- ![dialog2](../../static/img/integration/clock-in/dialog2.png) --> | Employee scanned an expired QR Code |  
| <!-- ![dialog3](../../static/img/integration/clock-in/dialog3.png) --> | Employee generated the QR Code under a different company and is not allowed to clock in / out |  
| <!-- ![dialog4](../../static/img/integration/clock-in/dialog4.png) --> | Employee is under a different branch and is not allowed to clock in / out |  
| <!-- ![dialog5](../../static/img/integration/clock-in/dialog5.png) --> | Employee has successfully clocked in |  
| <!-- ![dialog6](../../static/img/integration/clock-in/dialog6.png) --> | Employee has successfully clocked out |  

## Settings

    <!-- ![setting](../../static/img/integration/clock-in/setting.png) -->

    - **Camera View:** User can switch the default direction of the QR Scanner camera  
    - **Screen Wake Sensitivity:** User can adjust how sensitive they want their scanner to wake up from motion detection after entering black screen  