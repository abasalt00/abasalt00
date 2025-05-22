<div align="center">

# Quantum Engineer | Neuroengineer
*Developing next-generation neural interfaces through quantum sensing and miniaturized electrophysiology*

<table>
<tr>
<td width="33%">

### 🔬 Research Focus
- **Quantum Sensing** with NV Centers
- **Miniaturized Neural Interfaces**
- **Brain-Computer Interface Systems**
- **Open-Source Medical Devices**

</td>
<td width="33%">

### ⚛️ Quantum Neural Interface

<svg viewBox="0 0 300 150" xmlns="http://www.w3.org/2000/svg" width="300" height="150">
  <defs>
    <radialGradient id="quantumGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:0.8" />
      <stop offset="100%" style="stop-color:#2563eb;stop-opacity:0.2" />
    </radialGradient>
    
    <linearGradient id="neuralPath" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3b82f6;stop-opacity:0.3" />
      <stop offset="50%" style="stop-color:#2563eb;stop-opacity:0.8" />
      <stop offset="100%" style="stop-color:#3b82f6;stop-opacity:0.3" />
    </linearGradient>
    
    <filter id="quantumBlur">
      <feGaussianBlur in="SourceGraphic" stdDeviation="0.5"/>
    </filter>
  </defs>
  
  <!-- Background neural network -->
  <g opacity="0.3">
    <circle cx="40" cy="35" r="2" fill="#2563eb">
      <animate attributeName="r" values="2;4;2" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="120" cy="30" r="2" fill="#3b82f6">
      <animate attributeName="r" values="2;3;2" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="200" cy="40" r="2" fill="#2563eb">
      <animate attributeName="r" values="2;4;2" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="260" cy="35" r="2" fill="#3b82f6">
      <animate attributeName="r" values="2;3;2" dur="1.8s" repeatCount="indefinite"/>
    </circle>
    
    <line x1="40" y1="35" x2="120" y2="30" stroke="url(#neuralPath)" stroke-width="1">
      <animate attributeName="stroke-opacity" values="0.3;0.8;0.3" dur="2s" repeatCount="indefinite"/>
    </line>
    <line x1="120" y1="30" x2="200" y2="40" stroke="url(#neuralPath)" stroke-width="1">
      <animate attributeName="stroke-opacity" values="0.3;0.8;0.3" dur="2.2s" repeatCount="indefinite"/>
    </line>
    <line x1="200" y1="40" x2="260" y2="35" stroke="url(#neuralPath)" stroke-width="1">
      <animate attributeName="stroke-opacity" values="0.3;0.8;0.3" dur="1.8s" repeatCount="indefinite"/>
    </line>
  </g>
  
  <!-- Quantum NV Centers -->
  <g>
    <g transform="translate(70,70)">
      <circle r="6" fill="url(#quantumGlow)" filter="url(#quantumBlur)">
        <animate attributeName="r" values="6;9;6" dur="3s" repeatCount="indefinite"/>
      </circle>
      <polygon points="0,-3 2.5,1.5 -2.5,1.5" fill="#2563eb" opacity="0.8">
        <animateTransform attributeName="transform" type="rotate" values="0;360" dur="4s" repeatCount="indefinite"/>
      </polygon>
    </g>
    
    <g transform="translate(150,85)">
      <circle r="5" fill="url(#quantumGlow)" filter="url(#quantumBlur)">
        <animate attributeName="r" values="5;8;5" dur="2.5s" repeatCount="indefinite"/>
      </circle>
      <polygon points="0,-2.5 2,1.2 -2,1.2" fill="#3b82f6" opacity="0.9">
        <animateTransform attributeName="transform" type="rotate" values="360;0" dur="3.5s" repeatCount="indefinite"/>
      </polygon>
    </g>
    
    <g transform="translate(230,75)">
      <circle r="5.5" fill="url(#quantumGlow)" filter="url(#quantumBlur)">
        <animate attributeName="r" values="5.5;8.5;5.5" dur="2.8s" repeatCount="indefinite"/>
      </circle>
      <polygon points="0,-2.8 2.3,1.4 -2.3,1.4" fill="#2563eb" opacity="0.7">
        <animateTransform attributeName="transform" type="rotate" values="0;360" dur="5s" repeatCount="indefinite"/>
      </polygon>
    </g>
  </g>
  
  <!-- Brain wave signal -->
  <g transform="translate(0,110)">
    <path d="M0,15 Q40,5 80,15 T160,15 T240,15 T300,15" 
          stroke="#2563eb" 
          stroke-width="1.5" 
          fill="none" 
          opacity="0.6">
      <animate attributeName="d" 
               values="M0,15 Q40,5 80,15 T160,15 T240,15 T300,15;
                       M0,15 Q40,25 80,15 T160,15 T240,15 T300,15;
                       M0,15 Q40,5 80,15 T160,15 T240,15 T300,15" 
               dur="3s" 
               repeatCount="indefinite"/>
    </path>
  </g>
  
  <!-- Quantum interference -->
  <g opacity="0.3">
    <circle cx="150" cy="75" r="30" fill="none" stroke="#3b82f6" stroke-width="0.8">
      <animate attributeName="r" values="30;45;30" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="stroke-opacity" values="0.3;0.1;0.3" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="150" cy="75" r="20" fill="none" stroke="#2563eb" stroke-width="0.8">
      <animate attributeName="r" values="20;35;20" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="stroke-opacity" values="0.5;0.2;0.5" dur="3s" repeatCount="indefinite"/>
    </circle>
  </g>
  
  <!-- Status -->
  <g transform="translate(15,135)">
    <circle r="1.5" fill="#10b981">
      <animate attributeName="fill" values="#10b981;#3b82f6;#10b981" dur="1s" repeatCount="indefinite"/>
    </circle>
    <text x="6" y="3" font-family="monospace" font-size="8" fill="#374151">NV Active</text>
  </g>
  
  <g transform="translate(80,135)">
    <circle r="1.5" fill="#f59e0b">
      <animate attributeName="fill" values="#f59e0b;#2563eb;#f59e0b" dur="1.2s" repeatCount="indefinite"/>
    </circle>
    <text x="6" y="3" font-family="monospace" font-size="8" fill="#374151">Neural Sync</text>
  </g>
  
  <g transform="translate(160,135)">
    <circle r="1.5" fill="#ef4444">
      <animate attributeName="fill" values="#ef4444;#3b82f6;#ef4444" dur="0.8s" repeatCount="indefinite"/>
    </circle>
    <text x="6" y="3" font-family="monospace" font-size="8" fill="#374151">Q-Coherence</text>
  </g>
</svg>

</td>
<td width="33%">

### 🛠️ Technical Stack
- **Languages:** Python, MATLAB, C++
- **Hardware:** KiCad, Autodesk Suite  
- **Domains:** Signal Processing, Bioengineering
- **Platforms:** Lab Equipment Integration

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=12&pause=1000&color=2563EB&width=250&lines=Quantum+sensing+active...;Neural+patterns+detected...;Interface+optimization..." alt="Status" />

</td>
</tr>
</table>

</div>
