<p align="center"><h1>🧠 Awesome Multimodal Prompts </h1></p>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
[![Code License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/yzfly/Awesome-Multimodal-Prompts/blob/main/LICENSE)

Welcome to the "Awesome Multimodal Prompts" repository! This is a collection of prompt examples to be used with the Multimodal LLM (GPT-4V).

To get started, simply clone this repository and use the prompts in the README.md file as input for [GPT-4V](https://chat.openai.com/). You can also use the prompts in this file as inspiration for creating your own.

We hope you find these prompts useful and have fun!

## Contents
- [Contents](#contents)
- [Articles and Resources](#articles-and-resources)
  - [Math Formula Recognition](#math-formula-recognition)
  - [Read Doctor's Notes](#read-doctors-notes)
  - [Code Generation from Figma screenshots](#code-generation-from-figma-screenshots)
  - [Edit Code by Edit Image](#edit-code-by-edit-image)
  - [Code Conversion for developer](#code-conversion-for-developer)

## Articles and Resources

* [ChatGPT can now see, hear, and speak](https://openai.com/blog/chatgpt-can-now-see-hear-and-speak)
* [ChatGPT多模态解禁，网友玩疯！拍图即生代码，古卷手稿一眼识别，图表总结超6](https://mp.weixin.qq.com/s/FfiPJpxNrQpHxmOxBpDyHg)

### Math Formula Recognition

Upload your [image of Math Formula] and then use following prompts:
```
Recognize the Math Formula in the image and output in LaTex Code.
```

### Read Doctor's Notes

> https://twitter.com/wats_updog/status/1707236519285596358

Upload your [image of Doctor's Notes] and then use following prompts:
```
My doctor wrote me this prescription. Please help me understand what is it for?
```

### Code Generation from Figma screenshots

> https://twitter.com/mckaywrigley/status/1707796170905661761

Upload your [SCREENSHOT of Figma] and then use following prompts:

```
I need you to do the following things:

1.Create the pictured component
2. Also create the tab for the passsword flow
- Should indlude password and confirm press
- Should have functlonality to check that they are the same
3. The component should look exactly like the one shown and include all of its components.

Here are your guidelines:
- Use Nodejs (the app is already set up)
- Use Tallwind CSS for styiing.
- Use TypeScript.

```

### Edit Code by Edit Image

This is a cool follow up demo of using the mobile app’s “draw on image” feature to edit the component we just generated.

> https://twitter.com/mckaywrigley/status/1707801301093068880


### Code Conversion for developer

Upload your [SCREENSHOT of Python code] and then use following prompts:
```
Convert a SCREENSHOT of Python code to Javascript.
```

