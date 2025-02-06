# Flutter 3D Rotating Cube

This Flutter project demonstrates a 3D rotating cube using the `Transform` widget and `Matrix4` for applying perspective and rotation transformations. The cube continuously rotates along the X, Y, and Z axes using animation controllers.
![Flutter Version](https://img.shields.io/badge/Flutter-3.27-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Features
- Uses `AnimationController` for smooth rotation.
- Applies transformations using `Matrix4`.
- Creates a cube using six `Container` widgets with different colors.
- Uses `AnimatedBuilder` to rebuild the widget tree efficiently.

## Getting Started

### Prerequisites
Ensure you have Flutter installed on your system.

- Install Flutter: [Flutter Installation Guide](https://flutter.dev/docs/get-started/install)
- Clone the repository:
  ```sh
  git clone https://github.com/yourusername/flutter_3d_cube.git
  cd flutter_3d_cube
  ```

### Running the Application
Run the app using the following command:
```sh
flutter run
```

## File Structure
```
flutter_3d_cube/
│-- lib/
│   │-- main.dart  # Entry point of the application
│-- pubspec.yaml   # Dependencies
│-- README.md      # Documentation
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Video
<video src="https://github.com/user-attachments/assets/de85d4e5-76c7-438e-a248-cf21e26182e8" 
       width="500" 
       height="350" 
       controls>
</video>

