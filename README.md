Hi!

This project demonstrates how to create images using the Stable Diffusion base model for image generation from AWS Bedrock with the boto3 SDK inside a Jupyter Notebook.

The following libraries are required for the project:

- base64 (for decoding and encoding images as the API returns a base64 encoded image)
- os and dotenv (to utilize environment variables for concealing private AWS access information)
- random (to generate random numbers for the seed, producing a different image each time the API is called)
- boto3 (AWS SDK for Python)
- json (for API-requests)
- io, PIL (Pillow) and IPython do display the generated image inside the Windows Photo Viewer as well as in the Notebook

The code is explained through comments inside the notebook :)
