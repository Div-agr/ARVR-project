# 🚗 The Car Driving Simulator VR
A fully immersive car driving simulator in Unity with VR support using Meta Quest 2 and NITTO Drive 1 Pro steering wheel. The simulator features realistic car physics, VR head tracking, and controller-based driving mechanics.  

## 👥 Contributors  
| Name | Roll Number |
|------|--------------|
| Divyansh Kumar Agrawal | 106123035 |
| Md Bhaul Islam | 106123081 |
| Rahul Merotha | 106123103 |

---

## 🔥 Features  
✅ **Realistic Driving Physics:**  
- Smooth acceleration, braking, and steering.  
- Natural vehicle movement with proper gravity and wheel colliders.  

✅ **VR Integration:**  
- Supports Meta Quest 2 with OpenXR.  
- first-person driver view.  

✅ **Steering Wheel Controls:**  
- NITTO Drive 1 Pro compatibility with Xbox mode.  
- Accurate steering, acceleration, braking, and reverse control.  

✅ **Camera System:**  
- VR camera rig follows the car with realistic driver perspective.  
- Multiple views: Driver view, hood view, and free-look.  

✅ **Optimized Performance:**  
- Uses Single-Pass Rendering for better VR performance.  
- Stable car physics to prevent flipping.
      
✅ **NO Need For any Special item:**
- You Can Play this Game Via any controller
- No need For VR (VR is for Better experince ) to Play
---

## 🛠️ Tech Stack & Tools  
- **Game Engine:** Unity
- **Programming Language:** C#
- **IDE:** Visual Studio Code  
- **Version Control:**  Git and Github  
- **Assets:**  
    - Vehicle Physics Pro (VPP) → For realistic car behavior   
    - XR plugins for Meta Quest 2  

---

## 🔧 Installation & Setup  

✅ **1. Clone the Repository**  
```bash
git clone https://github.com/Div-agr/ARVR-project.git
cd The_Car_Simulator_-VR-
```

✅ **2. Unity Configuration**  
- Open the project in **Unity 2022.3.34f1** or higher.  
- Go to **Edit → Project Settings → XR Plug-in Management:**  
    - Enable **OpenXR**.  
    - Select **Meta Quest Support**.  

- **Player Settings:**  
    - Go to **Edit → Project Settings → Player → Other Settings**.  
    - Set **Color Space** to Linear.  
    - Set **Rendering Path** to Forward.  
    - Check **Single-Pass Instanced Rendering**.  

- **Enable VR Preview:**  
    - Go to **Oculus App → Devices → Air Link → Pair with Unity**.  
    - Ensure **Oculus Link** is enabled.  

---

## 🎮 Steering Wheel Controls  

| Button                | Action               | Keyboard Input       |
|-----------------------|----------------------|------------------------|
| **Steering**          | Left / Right Turn    | `left/right buttons`        |
| **White Button (Right)**| Brake                | `Down arrow key`    |
| **White Button (Left)**| Accelerate           | `Up arrow key`    |
| **Metal LB**           | Respawn the Car      | `Esc`    |
| **Metal RB**           | Change Toggle/View   | `Esc`    |
| **X Button**           | Reverse Gear         | `capslock`    |
| **Y Button**           | Neutral Gear         | `capslock`    |
| **B Button**           | Increase Gear        | `tab`    |
| **A Button**           | Turn On Engine       | `start`    |


✅ **VR Controls**  
- **Head Tracking:**  
    - Move your head to look around inside the car.  
- **Car Movement:**  
    - Use the steering wheel for left and right movement.  
    - Accelerate, brake, and reverse using the pedal system.  
- **Reset View:**  
    - Click the right joystick to re-center the VR view.  

---

## 🚀 How to Play  
1. Start Unity with your **Meta Quest 2** connected via **Air Link**.  
2. Press **Play** in Unity.  
3. Put on the **Meta Quest 2** headset.  
4. Use the steering wheel for driving and VR headset for a realastic view.  
5. Enjoy the immersive driving experience! 🚗🕶️  

---

## ⚙️ Customization  

✅ **Changing the Car Model:**  
- Go to **Assets → Prefabs → Car** → Replace the model with your custom car.  
- Ensure the wheel colliders and rigid body parameters are properly configured.  

✅ **Adjusting VR Camera Position:**  
- Move the **XR Origin** object in the hierarchy to adjust the camera height and position.  

✅ **Modifying Car Physics:**  
- Open the **CarController** script → Adjust values like:  
    - `steeringSpeed`, `maxSpeed`, and `acceleration`.  

✅ **Change Steering Sensitivity:**  
- Modify the sensitivity in **Input Actions** for smoother steering.  

---

## 🛠️ Troubleshooting  

✅ **VR Not Detecting in Unity:**  
- Ensure **Air Link** is enabled in Meta Quest 2 settings.  
- Restart Unity if VR is not detected.  

✅ **Steering Wheel Not Recognized:**  
- Set the **NITTO Drive 1 Pro** to Xbox Mode.  
- Restart Unity after switching controller modes.  

✅ **Laggy Performance:**  
- Lower the **Fixed Timestep** to `0.01` in **Project Settings → Time**.  
- Reduce shadow quality and enable **Single-Pass Rendering**.  

---

## 🛠️ Future Enhancements  
🔥 **Multiplayer Mode:** Drive with friends in VR multiplayer mode.  
🔥 **Weather Effects:** Realistic rain, fog, and snow effects.  
🔥 **Day-Night Cycle:** Dynamic lighting conditions.  
🔥 **Custom Cars:** Add new car models with unique physics.  

---


---

## 🎯 Credits  
- **Unity Asset Store Assets** → Vechile Physics Pack   
- **Meta Quest 2** → For VR integration.  

---
