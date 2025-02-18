# Image-Generation-using-stable-diffusion-Comfy-UI
Aicte 4 week internship by Techsakshm</br>
<h1>Part 1: Stable Diffusion</h1></br>
Installing the libraries (xformers library to memory optimization)<br>
Pipeline for image generation: Creating the prompt -> Generating the image -> Saving the result</br>
Generating multiple images</br>
<u><b>Parameters</b></u>: Seed, Inference steps, Guidance scale (CFG), Image size (dimensions), Negative prompt</br>
<b><u>Other models</u></b>: SD v1.5, SD v2.x, Fine-tuned models with specific styles</br>
<u>Changing the scheduler</u>: PNDM (default), DDIM Scheduler, K-LMS Scheduler, Euler Ancestral Discrete Scheduler (Euler A), DPM Scheduler</br>
<h1>Part 2: Prompt Engineering</h1></br>
Exploring the prompts: Subject / object, Action and location, Type, Style, Colors, Artist, Resolution, Site. And Other attributes: Ilumination, Negative prompts</br>
<b><u>Use cases</u>:</b> Generating arts, Generating photographs, Generating landscapes, Generating 3D images, Generating drawings, Generating architectures</br>
Improving the results using custom models: Anything (cag/anything-v3-1), DreamShaper (Lykon/DreamShaper), Realistic Vision (SG161222/Realistic_Vision_V1.4), Analog Diffusion (wavymulder/Analog-Diffusion), Protogen (darkstorm2150/Protogen_x3.4_Official_Release), Mitsua Diffusion One (Mitsua/mitsua-diffusion-one)</br>
<h1>Part 3: Fine-tuning</h1></br>
Installing the libraries (accelerate transformers ftfy bitsandbytes==0.35.0 gradio natsort safetensors xformers)</br>
Loading the model</br>
<b><u>Training</u>:</b> Three components are needed: unique identifier, class name, images</br>
Convert the weights into (checkpoint)</br>
Inference (tests)</br>
<b><u>Generating images</u>:</b> Testing multiple prompts, More prompt examples: in the forest, in cairo, in cairo desert, in a western scene, in star wars, in mountain fuji, in the snow, etc.</br>
Saving the results.</br>
<h1>Part 4: Image-to-image</h1></br>
Installing the libraries (accelerate transformers ftfy bitsandbytes==0.35.0 gradio natsort safetensors xformers)</br>
Generating the image</br>
Strength parameter (intensity)</br>
Testing different styles</br>
Changing the input image</br>
Changing the scheduler</br>
Image to image "editing" (InstructPix2pix)</br>
<h1>Part 5: Inpainting</h1><br>
Installing the libraries (accelerate transformers ftfy bitsandbytes==0.35.0 gradio natsort safetensors xformers)</br>
Creating the prompt</br>
Exchanging the objects</br>
Comparing the results (Other image, Generating multiple images).</br>
<h1>Part 6: ControlNet</h1></br>
Installing the libraries (accelerate transformers xformers)</br>
Generating images using edges (ControlNet model + Canny Edge, Detecting edges using Canny Edge, fine-tuned model)</br>
Generating images using poses</br>
