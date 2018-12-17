
Based on [AR Core Ruler](https://learning.oreilly.com/videos/master-arcore-1-3/9781789537413/9781789537413-video3_1) lesson of AR Course. ([Mirror on udemy](https://www.udemy.com/master-arcore-in-unity-sdk-build-augmented-reality-apps/))

Github of the course: https://github.com/reigngt09/ARCore

### Steps
- Import Google AR Core SDK to Unity
- Open Hello AR example
  - Select Example Controller on the scene
  - Replace Andy Plane property with the prefab from this repository
  - Replace Text property
  - Replace the script
  - Be sure to apply andy and its line materials
- Configure Build Settings
  - Select Android Platform
  - In Player Settings
    - set unique name in Other Settings -> Package Name
    - set Android 7.0 in in Other Settings -> Minimum API Level
    - set ARCore supported in XS Settings
