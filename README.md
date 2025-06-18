# StopDoSvc.bat - Pause Delivery Optimization

This batch script stops the **Delivery Optimization** service (`DoSvc`) on Windows. This service is responsible for peer-to-peer update sharing used by Windows Update and Microsoft Store.

## 🛠 What It Does

- Stops the `DoSvc` service using `net stop`
- Changes the startup type to `manual` using `sc config`

## ⚠️ Important Notes

- Must be run as **Administrator**
- Only temporarily pauses the service — it may restart after reboot unless disabled permanently.
- Disabling this service may affect Windows Update delivery performance.

## 💻 How to Use

1. Right-click `StopDoSvc.bat`
2. Select **Run as Administrator**
3. Press an
