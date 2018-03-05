# Post-Process-Depth-Grayscale-Unity-3D
PostProcessDepthGrayscale :
In this project we were trying to get the depth buffer, we used a render texture, which is a special type of texture that’s created and updated in realtime. The depth buffer, or depth texture, is actually just a render texture that contains values of how far objects in the scene are from the camera. First, i generated the depth texture from the camera , which can be done with Camera.depthTextureMode. Then,we used OnRenderImage function to pass it to the shader for processing. It will be a simple vertex and fragment shader. Basically, it will read the depth texture from the camera, then display the depth value at each screen coordinate.
