# 🛰️ Overwatch Drone Workflow Checklist
### *Flight → Model → Render → Publish*

A step-by-step pipeline for creating professional drone-based inspection and 3D modeling content.  
Designed for **DJI Mini 4 Pro** + **Blender**, with integrations for **Pix4D / Metashape / WebODM**.

---

<details>
<summary>🧭 <strong>1. Pre-Flight Planning</strong></summary>

#### ☑️ Site Prep
- [ ] Confirm weather, wind (<15 mph), and daylight  
- [ ] Clear flight area of trees, people, and obstacles  
- [ ] Confirm FAA compliance & airspace (use B4UFLY app)  
- [ ] Obtain property owner permission  

#### ☑️ Equipment
- [ ] DJI Mini 4 Pro batteries fully charged  
- [ ] SD card formatted  
- [ ] Gimbal clean, props intact  
- [ ] Controller + phone/tablet charged  

#### ☑️ Mission Setup
- [ ] Plan grid flight pattern (75–80% overlap)  
- [ ] Camera: Manual mode (ISO 100, shutter ~1/500s, focus to infinity)  
- [ ] Capture altitude: 50–100 ft (for property-scale modeling)  
- [ ] Enable GPS logging if available  

</details>

---

<details>
<summary>📸 <strong>2. Image Capture</strong></summary>

#### ☑️ Flight Execution
- [ ] Take-off and hover for stability check  
- [ ] Fly automated grid pattern (front + side overlap)  
- [ ] Capture nadir (top-down) and angled oblique shots  
- [ ] Record 4K video for marketing reel (optional)  

#### ☑️ Data Management
- [ ] Land and power off safely  
- [ ] Transfer photos to your project folder:
- [ ] Backup to cloud or external drive  

</details>

---

<details>
<summary>🧩 <strong>3. 3D Reconstruction</strong></summary>

#### ☑️ Choose Photogrammetry Software
- [ ] **Pix4Dmapper** – enterprise-grade precision  
- [ ] **Agisoft Metashape** – pro desktop workflow  
- [ ] **WebODM** – open-source, flexible  

#### ☑️ Processing Steps
1. Import images (ensure EXIF GPS tags)  
2. Align photos → generate sparse point cloud  
3. Build dense cloud → mesh → texture  
4. Export 3D model (.OBJ / .GLTF / .FBX)

</details>

---

<details>
<summary>🎨 <strong>4. Blender Post-Processing</strong></summary>

#### ☑️ Import & Clean
- [ ] Import mesh into Blender  
- [ ] Remove noise or floating geometry  
- [ ] Simplify mesh (Decimate Modifier if heavy)  

#### ☑️ Texturing & Lighting
- [ ] Apply baked textures or original photos  
- [ ] Add HDRI environment lighting  
- [ ] Set up realistic sun & shadow system  

#### ☑️ Animation (optional)
- [ ] Create flyaround camera path  
- [ ] Add pan/zoom effects for realism  

#### ☑️ Rendering
- [ ] Choose engine → **Eevee (fast)** or **Cycles (realistic)**  
- [ ] Render stills (for portfolio) + short video (for social)  
- [ ] Export `.png` and `.mp4` outputs  

</details>

---

<details>
<summary>🌐 <strong>5. Delivery & Portfolio Integration</strong></summary>

#### ☑️ Deliverables
- [ ] 3D Model File (.GLTF / .FBX)  
- [ ] Rendered Images (Marketing)  
- [ ] 30–60 sec Flythrough Video  
- [ ] Optional Sketchfab Upload  

#### ☑️ Website Integration
- [ ] Add renders/models to portfolio section  
- [ ] Include credit: *“Captured, Modeled, and Rendered by Overwatch”*  
- [ ] Write short description of workflow & tools used  

</details>

---

### ✅ End Goal
By the end of your first project, you’ll have:
- One complete 3D inspection model  
- Rendered visual content for your website  
- Your first case study for clients like **Dream House Builders**  
- A reusable pipeline for future Overwatch projects

---

> 🧰 *Tools Used:* DJI Mini 4 Pro · Pix4D / WebODM · Blender · Sketchfab · Jekyll  
> 🏗️ *Company:* Overwatch Drone Inspections  
> 🌎 *Site:* [khaledadad.com/drone-inspections-landing](https://www.khaledadad.com/drone-inspections-landing/)
