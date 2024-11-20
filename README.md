# <h1 align="center" style="font-size: 2.5rem; color: #4CAF50;">🚀 Smart Path Finder</h1>

<p align="center">
  <b>An Interactive Pathfinding Visualization Tool Built with React.js</b><br/>
  Visualize the shortest path between two points using <strong>Dijkstra's Algorithm</strong>.
</p>

<p align="center">
  <a href="https://github.com/Arvind7Goud/shortestpathfinder"><img src="https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"></a>
  <img src="https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge">
</p>

---

## <h2 style="font-size: 2rem; color: #f39c12;">🌟 Features</h2>

<ul style="font-size: 1.1rem;">
  <li>🖱️ <b>Interactive Grid</b>: Set start and end points, add obstacles, and customize paths.</li>
  <li>🔍 <b>Dijkstra's Algorithm</b>: Real-time visualization of the shortest path.</li>
  <li>📱 <b>Responsive Design</b>: Fully functional across devices and screen sizes.</li>
  <li>🔄 <b>Reset Functionality</b>: Clear the grid to try new configurations easily.</li>
</ul>

---

## <h2 style="font-size: 2rem; color: #3498db;">🛠️ Technologies Used</h2>

<div style="font-size: 1.2rem; line-height: 1.5;">
  <p><strong>Frontend:</strong> React.js</p>
  <p><strong>Algorithm:</strong> Dijkstra's Algorithm</p>
  <p><strong>Styling:</strong> CSS</p>
</div>

---

## <h2 style="font-size: 2rem; color: #9b59b6;">🚀 How It Works</h2>

<ol style="font-size: 1.1rem;">
  <li>Set up the grid by placing start and end points.</li>
  <li>Add obstacles to simulate barriers.</li>
  <li>Run the algorithm to calculate the shortest path.</li>
  <li>Visualize the algorithm’s steps and path in real time.</li>
  <li>Reset the grid for new configurations.</li>
</ol>

---

## <h2 style="font-size: 2rem; color: #e74c3c;">🖥️ Installation and Setup</h2>

<p style="font-size: 1.1rem;">
Follow these steps to set up the project locally:
</p>

<pre style="background-color: #f4f4f4; padding: 1rem; border-radius: 8px;">
1️⃣ Clone the Repository:
<code>
git clone https://github.com/Arvind7Goud/shortestpathfinder.git
cd shortestpathfinder
</code>

2️⃣ Install Dependencies:
<code>
npm install
</code>

3️⃣ Start the Development Server:
<code>
npm start
</code>

4️⃣ Open the Application:
<code>
http://localhost:3000
</code>
</pre>

---

## <h2 style="font-size: 2rem; color: #1abc9c;">📂 Project Structure</h2>

```plaintext
shortestpathfinder/
├── public/         # Static assets
├── src/
│   ├── components/ # React components (Grid, Node, Controls)
│   ├── algorithms/ # Implementation of Dijkstra's Algorithm
│   ├── styles/     # CSS files
│   ├── App.js      # Main application logic
│   ├── index.js    # Application entry point
├── package.json    # Project metadata
