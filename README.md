# Bloch-Sphere-Simulator

![image](https://github.com/user-attachments/assets/5e6d9578-af40-41e3-b0e3-ab7c55681e08)

- [Bloch Sphere Simulator](https://miguell-j.github.io/Bloch-Sphere-Simulator/)


A web-based interactive quantum state visualization tool that allows users to explore and manipulate qubit states through a 3D representation of the Bloch sphere.

## Features

- Real-time 3D visualization of the Bloch sphere using Three.js
- Interactive controls for adjusting θ (theta) and φ (phi) angles
- Implementation of common quantum gates:
  - Pauli-X (NOT gate)
  - Hadamard (H)
  - Pauli-Z (Phase flip)
  - Pauli-Y
  - S gate (Phase gate)
  - T gate (π/8 gate)
- Quick access to basic quantum states:
  - |0⟩ (Ground state)
  - |1⟩ (Excited state)
  - |+⟩ (Superposition state)
  - |-⟩ (Negative superposition state)
- Real-time state information display:
  - Dirac notation
  - Vector notation with angles
- Responsive design that adapts to different screen sizes
- Animated state transitions
- Informative tooltips for all controls

## Technical Stack

- HTML5
- CSS3
- JavaScript
- Libraries:
  - Three.js (r128) - For 3D graphics rendering
  - Math.js (v9.4.4) - For complex number calculations

## Usage

1. Clone or download the repository
2. Open the HTML file in a modern web browser
3. Use the controls panel to interact with the visualization:
   - Adjust θ and φ angles using the sliders
   - Click quantum gate buttons to apply transformations
   - Use the base state buttons to set specific states
   - Click "Reset" to return to the initial state (|0⟩)

## Visual Elements

- Wireframe sphere representing the Bloch sphere
- Color-coded axes (x, y, z) with labels
- Cyan arrow indicating the current quantum state
- Background grid for better spatial perception
- Information panels:
  - Controls panel (left)
  - State information panel (right)
  - Educational information panel (bottom)

## Educational Value

The simulator serves as an educational tool for:
- Understanding quantum state representation
- Visualizing qubit transformations
- Learning about quantum gates and their effects
- Exploring the geometric interpretation of quantum states

## Browser Compatibility

The simulator requires a modern web browser with WebGL support. Tested on:
- Chrome
- Firefox
- Safari
- Edge

## Performance Notes

- The sphere rotation animation is optimized with minimal CPU usage
- Smooth state transitions are implemented using spherical interpolation
- Responsive design ensures proper rendering on various screen sizes

## Future Improvements

Potential areas for enhancement:
- Additional quantum gates
- Custom gate sequence creation
- State measurement simulation
- Multiple qubit visualization
- Export/import of quantum states
- Interactive tutorials
- Performance optimizations for mobile devices

## License

This project is available for educational and research purposes. Please attribute the original source when using or modifying the code.
