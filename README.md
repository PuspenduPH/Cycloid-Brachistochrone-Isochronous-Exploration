# ⏱️ The Cycloid: Nature’s Fastest Curve

This repository explores two fascinating physical and mathematical properties of the **Cycloid curve**:

- 📉 **Brachistochrone** — the curve of **fastest descent** under gravity without any friction
- ⏲️ **Isochronous** — objects released from any point on the curve reach the bottom **simultaneously**

  <table>
    <tr>
      <th>Tautochrone Curve </th>
      <th>Brachistochrone Curve </th>
    </tr>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/36c2817b-3feb-42ee-bc8e-fa72fd81f0de" width="450"/></td>
      <td><img src="https://github.com/user-attachments/assets/669d627b-5e0c-4b20-bed1-0eb74ec260d7" width="450"/></td>
    </tr>
  </table>



## 📘 What's Inside

This repository contains:

- 📓 **`cycloid_analysis.ipynb`** — A detailed Jupyter Notebook containing derivations, visualizations, and animations.
- 📂 **`IMAGES/`** — Static figures and diagrams used throughout the notebook.
- 📂 **`ANIMATION/`** — Rolling ball animations along cycloid, parabola, circular arc, and straight line.
- 📄 **`requirements.txt`** — Python dependencies to run the notebook smoothly.


## ✨ Highlights

### 📐 Derivations and Comparisons
- Derived the **equation of the Brachistochrone** using energy conservation and the **Euler-Lagrange equation**
- Compared the cycloid to a **parabolic path**, **circular arc**, and **straight line** — all sharing the same endpoints

### ⏳ Time of Descent Calculations
- **Analytical expressions** for cycloid and straight line
- **Numerical integration** (`scipy.integrate.quad`) for more complex paths

### 🎥 Realistic Rolling Ball Animation
- Accounted for the **normal vector offset** to make the ball appear to roll *on* the curve, not inside it

  <img src="https://github.com/user-attachments/assets/411796d4-b5e7-48a6-b7ad-783b4dd7d40f" width="850"/>


### 📊 Slope Comparison and Timing Table
- Compared the cycloid to **lines with varying slopes**
- Included a table showing descent times vs intermediate cycloid times
  
  <img src="https://github.com/user-attachments/assets/eddad8aa-1345-4b6c-9296-e7d86636c671" width="700"/>


### ⏲️ Isochronous Demonstration
- Multiple balls released from different heights on the **same cycloidal path**
- All balls reach the bottom **at the same time**
- Extended to **3D animation** across multiple cycloidal paths


## 🛠️ Setup

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/Cycloid-Brachistochrone-Isochronous-Exploration.git
cd Cycloid-Brachistochrone-Isochronous-Exploration
pip install -r requirements.txt
````

Then launch the notebook:

```bash
jupyter notebook cycloid_analysis.ipynb
```

## 📎 License

This project is licensed under the MIT License.


