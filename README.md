# EX NO: 1  Material Effects in Unreal Engine

## Aim
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

## Procedure

1. **Create a New Material:**
   - Open Unreal Engine.
   - In the Content Browser, right-click and select **Material**.
   - Name it `M_EffectsDemo`.

2. **Apply Base Color:**
   - Open the material.
   - Add a **Vector Parameter** or **Constant3Vector** node and connect it to the **Base Color** input.

3. **Add Emissive Effect:**
   - Add a **Multiply** node.
   - Connect a **Constant3Vector** (for emissive color) and a **Scalar Parameter** (for intensity).
   - Connect the result to the **Emissive Color** input.

4. **Control Roughness:**
   - Add a **Scalar Parameter** node and connect it to the **Roughness** input.
   - Lower values = shinier surface, higher values = rougher surface.

5. **Control Metallic Property:**
   - Add a **Scalar Parameter** node and connect it to the **Metallic** input.
   - 0 = non-metal, 1 = fully metallic.

6. **Save and Apply Material:**
   - Save the material.
   - Apply it to any mesh in the scene (like a sphere or cube) to preview the results.
  
     
## Output

![image](https://github.com/user-attachments/assets/903f240b-f9b7-4f2d-bf50-013ebebd7ea8)


![image](https://github.com/user-attachments/assets/3aaea163-8335-42c9-af3c-46adac71cb00)



## Result
Successfully implemented a material in Unreal Engine showcasing:
- Emissive glow using emissive color and intensity.
- Variable surface roughness to simulate different textures.
- Metallic appearance adjustment to reflect light like real-world metals.

This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
