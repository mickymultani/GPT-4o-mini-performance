# GPT-4o-mini-performance
GPT-4o-mini : Quick setup to test chat performance of various Open AI LLMs

Clone the repo, replace the open AI key with your key, run the cells and choose the model per the prompt. 

In my limited tests:

1. GPT-4o-mini is ~69% faster than GPT-4-Turbo and ~58% faster than GPT-4o.
2. GPT-4o also consumed the least number of tokens to provide a meaningful answer.
3. GPT-4o-mini output was also on par with GPT-4o quality, both of whih were significantly better than GPT-4 Turbo.

---------------------------------------------------------------------------------------------------------------------
Sample reponse:

Select a model:
1. gpt-3.5-turbo
2. gpt-4
3. gpt-4-turbo
4. gpt-4o
5. gpt-4o-mini
Enter your choice (or 0 to quit): 3

Chatting with gpt-4-turbo. Type 'quit' to exit.
You: why is the sky blue?
Bot: The blue color of the sky is primarily due to a phenomenon called Rayleigh scattering. Sunlight, which consists of light of multiple wavelengths, interacts with molecules in the Earth's atmosphere.

When sunlight enters the atmosphere, it collides with the particles and gases there. These particles are much smaller than the wavelength of visible light, and when light hits them, the shorter wavelengths (blue and violet) are scattered more widely than the longer wavelengths (red and orange). 

Although violet light is scattered even more than blue light, the sky doesn't appear violet because our eyes are more sensitive to blue light and because much of the violet light is absorbed by the upper layers of the atmosphere.

This scattering causes the sky to appear blue most of the time. Additionally, at sunrise and sunset, the sky can appear red and orange because the sun's light passes through more of the atmosphere, scattering short-wavelength light (blue and violet) out of the line of sight and allowing longer wavelengths (red and orange) to reach observers' eyes.
Response time: 8.19 seconds
Input tokens: 6
Output tokens: 206
You: quit

Total tokens used in this session:
Input tokens: 6
Output tokens: 206
Total tokens: 212

Select a model:
1. gpt-3.5-turbo
2. gpt-4
3. gpt-4-turbo
4. gpt-4o
5. gpt-4o-mini
Enter your choice (or 0 to quit): 4

Chatting with gpt-4o. Type 'quit' to exit.
You: why is the sky blue?
Bot: The sky appears blue because of a phenomenon called Rayleigh scattering. When sunlight enters Earth's atmosphere, it encounters molecules and small particles that scatter the light in different directions. Sunlight, or white light, is made up of various colors, each with different wavelengths. Blue light has a shorter wavelength and higher energy compared to other colors like red or yellow.

Shorter wavelengths of light, such as blue and violet, are scattered more effectively by the gases and particles in the atmosphere. However, our eyes are more sensitive to blue light and less so to violet light, partly because some of the violet light is absorbed by the upper atmosphere. As a result, we see the sky as blue.

During sunrise and sunset, the sky can look red or orange because the sun's light has to pass through more of the Earth's atmosphere. This increased distance scatters the shorter blue wavelengths out of your line of sight, leaving the longer red and orange wavelengths to dominate.
Response time: 5.81 seconds
Input tokens: 6
Output tokens: 190
You: quit

Total tokens used in this session:
Input tokens: 6
Output tokens: 190
Total tokens: 196

Select a model:
1. gpt-3.5-turbo
2. gpt-4
3. gpt-4-turbo
4. gpt-4o
5. gpt-4o-mini
Enter your choice (or 0 to quit): 5

Chatting with gpt-4o-mini. Type 'quit' to exit.
You: why is the sky blue?
Bot: The sky appears blue primarily due to a phenomenon called Rayleigh scattering. Sunlight, or white light, is made up of many colors, each with different wavelengths. When sunlight enters the Earth's atmosphere, it collides with gas molecules and small particles. 

Shorter wavelengths of light, such as blue and violet, are scattered in all directions more than longer wavelengths, like red and yellow. While both blue and violet light are scattered, our eyes are more sensitive to blue light, and some of the violet light is absorbed by the ozone layer in the atmosphere. As a result, we perceive the sky as predominantly blue during the day.

At sunrise and sunset, the sun's light passes through a thicker layer of the atmosphere, scattering the shorter blue wavelengths even more and allowing the longer wavelengths, such as red and orange, to dominate the sky's appearance at those times.
Response time: 2.54 seconds
Input tokens: 6
Output tokens: 174
You: quit

Total tokens used in this session:
Input tokens: 6
Output tokens: 174
Total tokens: 180

Select a model:
1. gpt-3.5-turbo
2. gpt-4
3. gpt-4-turbo
4. gpt-4o
5. gpt-4o-mini
Enter your choice (or 0 to quit): 0
