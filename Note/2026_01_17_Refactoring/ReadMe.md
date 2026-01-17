Lets check the disk for the July exploration to make the workshop on Texture, Computre Shader and ShaderGraph


- https://github.com/EloiStree/2026_02_09_WorkshopWhatNewInXR
- https://github.com/EloiStree/HelloUseCpuAndGpuOnQuest3

- be able to do in Hack Sensai ; Send Texture2D to web developer / REST and Flask.

https://github.com/EloiStree?tab=repositories&q=2025_06_&type=&language=&sort=
- https://github.com/EloiStree?tab=repositories&q=2025_07_&type=&language=&sort=
- https://github.com/EloiStree?tab=repositories&q=2025_08_&type=&language=&sort=


- Important: https://github.com/EloiStree/HelloUseCpuAndGpuOnQuest3/tree/main/MonsJuly2025
  - Sampling for testing: https://github.com/EloiStree/2025_07_06_ImageSampleForWebcamTelemetryTraining
 
- Test
  - https://github.com/EloiStree/2025_07_29_FontColorBytesTelemetryRead
  - https://github.com/EloiStree/2025_07_29_FontColorBytesTelemetry
  - Try color transmision and text :
    - https://github.com/EloiStree/2025_07_19_ScreenColorTransmission
  - Recover color from uWindowCapture
    - https://github.com/EloiStree/2025_06_24_uWindowCaptureToColor32
   
Python server to recover Image from the Quest on PC for AI, Open CV...:
- https://github.com/EloiStree/2025_06_13_QuestFlaskServerColor32
  

====

Source: https://github.com/oculus-samples/Unity-PassthroughCameraApiSamples
They use:
- [Meta MRUK (v81 or higher)](https://assetstore.unity.com/packages/tools/integration/meta-mr-utility-kit-272450)
- [Unity Sentis](https://unity.com/features/ai) for object detection
  
Play with Meta Camera Tool: https://github.com/EloiStree/2025_06_13_PlayWithCameraAPI.git 
[<img width="560" height="298" alt="image" src="https://github.com/user-attachments/assets/ec7b7b07-8d0f-4a33-ab4f-2c408dd7b255" />](https://github.com/EloiStree/2025_06_13_PlayWithCameraAPI.git)
- WebCamTextureManager : Will turn the Meta code to a Webcam
- PassthroughCameraPermissions : Will ask the Meta Camera permission
- WebCamTextureManagerRelayMono : Relay the webcam of Meta into a WebCamTexture in Unity
- ApplyWebCamTextureToRenderingMono: Apply the WebCamTexture to a renderer or material
- ApplyTexture2DToRenderingMono: Apply a given Texture2D to a renderer or material

Texture Toolbox: https://github.com/EloiStree/2025_06_13_ToolboxTexture2D
- TextureMono_WebCamTextureToRenderTexture : Turn a Webcam Texture to a RenderTexture
- TextureMono_RenderTextureToFileRelativeSaveWithDate : Allows to save RendererAsTexture with the date in it.

https://github.com/EloiStree/2025_06_13_upm_texture2d_to_flask:
- ProcessImageForDataAsColor32HTTP Send image to an Flask URL with widht and height in front.

https://github.com/EloiStree/2025_06_13_python_texture2d_flask_server_color32:
- Allows to have a python flask server to process given Texture2D of Unity from webcam.
