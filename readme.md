# Ultimate Color Reference Guide

This guide covers all major color formats, gradients, effects, and styling techniques in CSS/HTML.

## Table of Contents
1. [Basic Color Formats](#basic-color-formats)
2. [Advanced Color Formats](#advanced-color-formats)
3. [Gradients](#gradients)
4. [Color Effects](#color-effects)
5. [Color Schemes](#color-schemes)
6. [CSS Variables](#css-variables)
7. [System Colors](#system-colors)
8. [Color Functions](#color-functions)
9. [Color Palettes](#color-palettes)
10. [Browser Support](#browser-support)

---

## Basic Color Formats

| Format         | Example            | Preview                                                                     |
|----------------|--------------------|-----------------------------------------------------------------------------|
| HEX (3-digit)  | `#F00`             | <div style="background-color:#F00; width:80px; height:30px;"></div>         |
| HEX (6-digit)  | `#FF0000`          | <div style="background-color:#FF0000; width:80px; height:30px;"></div>      |
| RGB            | `rgb(255, 0, 0)`   | <div style="background-color:rgb(255,0,0); width:80px; height:30px;"></div> |
| Named Color    | `red`              | <div style="background-color:red; width:80px; height:30px;"></div>          |

| Color Name      | HEX       | RGB           | Preview |
|-----------------|-----------|---------------|---------|
| Red             | `#FF0000` | `rgb(255,0,0)`| <div style="background-color:#FF0000; width:50px; height:20px;"></div> |
| Green           | `#00FF00` | `rgb(0,255,0)`| <div style="background-color:#00FF00; width:50px; height:20px;"></div> |
| Blue            | `#0000FF` | `rgb(0,0,255)`| <div style="background-color:#0000FF; width:50px; height:20px;"></div> |
| Yellow          | `#FFFF00` | `rgb(255,255,0)`| <div style="background-color:#FFFF00; width:50px; height:20px;"></div> |
| Cyan            | `#00FFFF` | `rgb(0,255,255)`| <div style="background-color:#00FFFF; width:50px; height:20px;"></div> |
| Magenta         | `#FF00FF` | `rgb(255,0,255)`| <div style="background-color:#FF00FF; width:50px; height:20px;"></div> |
| Black           | `#000000` | `rgb(0,0,0)`| <div style="background-color:#000000; width:50px; height:20px;"></div> |
| White           | `#FFFFFF` | `rgb(255,255,255)`| <div style="background-color:#FFFFFF; width:50px; height:20px; border:1px solid #000"></div> |

### Web-Safe Colors

| Color Name      | HEX       | Preview |
|-----------------|-----------|---------|
| Navy            | `#000080` | <div style="background-color:#000080; width:50px; height:20px;"></div> |
| Teal            | `#008080` | <div style="background-color:#008080; width:50px; height:20px;"></div> |
| Olive           | `#808000` | <div style="background-color:#808000; width:50px; height:20px;"></div> |
| Purple          | `#800080` | <div style="background-color:#800080; width:50px; height:20px;"></div> |
| Maroon          | `#800000` | <div style="background-color:#800000; width:50px; height:20px;"></div> |
| Gray            | `#808080` | <div style="background-color:#808080; width:50px; height:20px;"></div> |
| Silver          | `#C0C0C0` | <div style="background-color:#C0C0C0; width:50px; height:20px;"></div> |

### Popular Modern Colors

| Color Name      | HEX       | Preview |
|-----------------|-----------|---------|
| Pink            | `#FFC0CB` | <div style="background-color:#FFC0CB; width:50px; height:20px;"></div> |
| Lavender        | `#E6E6FA` | <div style="background-color:#E6E6FA; width:50px; height:20px;"></div> |
| Coral           | `#FF7F50` | <div style="background-color:#FF7F50; width:50px; height:20px;"></div> |
| Mint            | `#98FF98` | <div style="background-color:#98FF98; width:50px; height:20px;"></div> |
| Peach           | `#FFDAB9` | <div style="background-color:#FFDAB9; width:50px; height:20px;"></div> |
| Sky Blue        | `#87CEEB` | <div style="background-color:#87CEEB; width:50px; height:20px;"></div> |
| Beige           | `#F5F5DC` | <div style="background-color:#F5F5DC; width:50px; height:20px;"></div> |

### Grayscale

| HEX       | Preview |
|-----------|---------|
| `#111111` | <div style="background-color:#111111; width:50px; height:20px;"></div> |
| `#333333` | <div style="background-color:#333333; width:50px; height:20px;"></div> |
| `#555555` | <div style="background-color:#555555; width:50px; height:20px;"></div> |
| `#777777` | <div style="background-color:#777777; width:50px; height:20px;"></div> |
| `#999999` | <div style="background-color:#999999; width:50px; height:20px;"></div> |
| `#BBBBBB` | <div style="background-color:#BBBBBB; width:50px; height:20px;"></div> |
| `#DDDDDD` | <div style="background-color:#DDDDDD; width:50px; height:20px;"></div> |

## Advanced Color Formats

| Format        | Example                     | Description                             | Preview                                                                                                     |
|---------------|-----------------------------|-----------------------------------------|-------------------------------------------------------------------------------------------------------------|
| RGBA          | `rgba(255, 0, 0, 0.5)`      | Red with 50% opacity                    | <div style="background-color:rgba(255,0,0,0.5); width:80px; height:30px; border:1px solid #ddd"></div>      |
| HSL           | `hsl(120, 100%, 50%)`       | Pure green (Hue, Saturation, Lightness) | <div style="background-color:hsl(120,100%,50%); width:80px; height:30px;"></div>                            |
| HSLA          | `hsla(120, 100%, 50%, 0.3)` | Green with 30% opacity                  | <div style="background-color:hsla(120,100%,50%,0.3); width:80px; height:30px; border:1px solid #ddd"></div> |
| OKLCH         | `oklch(70% 0.3 120)`        | Perceptually uniform color space        | <div style="background-color:oklch(70% 0.3 120); width:80px; height:30px;"></div>                           |
| HWB           | `hwb(270 10% 10%)`          | Hue-Whiteness-Blackness                 | <div style="background-color:hwb(270 10% 10%); width:80px; height:30px;"></div>                             |

## Gradients

### Linear Gradients
```
background: linear-gradient(to right, #ff758c, #ff7eb3);
background: linear-gradient(45deg, #ff9a9e 0%, #fad0c4 100%);
background: linear-gradient(to bottom, transparent, rgba(0,0,0,0.5));
```
<div style="display:flex;gap:10px;margin:15px 0;"> <div style="background:linear-gradient(to right, #ff758c, #ff7eb3); width:100px; height:50px;"></div> <div style="background:linear-gradient(45deg, #ff9a9e, #fad0c4); width:100px; height:50px;"></div> <div style="background:linear-gradient(to bottom, transparent, rgba(0,0,0,0.5)); width:100px; height:50px; border:1px solid #ddd"></div> </div>

### Radial Gradients

```
background: radial-gradient(circle at center, #c9ffbf, #ffafbd);
background: radial-gradient(ellipse farthest-corner, #fbc2eb, #a6c1ee);
```
<div style="display:flex;gap:10px;margin:15px 0;"> <div style="background:radial-gradient(circle at center, #c9ffbf, #ffafbd); width:100px; height:50px;"></div> <div style="background:radial-gradient(ellipse farthest-corner, #fbc2eb, #a6c1ee); width:100px; height:50px;"></div> </div>

### Conic Gradients

```
background: conic-gradient(red, yellow, lime, aqua, blue, magenta, red);
```
<div style="background:conic-gradient(red, yellow, lime, aqua, blue, magenta, red); width:100px; height:100px; border-radius:50%;margin:15px 0;"></div>

## Color Effects

### Shadows

```
box-shadow: 10px 10px 20px rgba(0,0,0,0.2);
text-shadow: 2px 2px 4px #000000;
filter: drop-shadow(5px 5px 5px rgba(0,0,0,0.5));
```
<div style="display:flex;gap:20px;align-items:center;margin:15px 0;"> <div style="box-shadow:10px 10px 20px rgba(0,0,0,0.2); width:60px; height:60px; background:#4CAF50;"></div> <div style="text-shadow:2px 2px 4px #000; color:white; font-weight:bold; padding:10px;">Shadow Text</div> <img src="https://via.placeholder.com/60" style="filter:drop-shadow(5px 5px 5px rgba(0,0,0,0.5))"> </div>

### Blend Modes

```
background-blend-mode: multiply;
mix-blend-mode: screen;
```

<div style="position:relative; height:60px; margin:15px 0;"> <div style="background:linear-gradient(to right, #FF416C, #FF4B2B); width:100px; height:60px; position:absolute;"></div> <div style="background:linear-gradient(to right, #00BCD4, #3F51B5); width:100px; height:60px; position:absolute; left:30px; mix-blend-mode:screen;"></div> </div>

### Filters

```
filter: brightness(150%) saturate(200%) hue-rotate(90deg);
```

<div style="display:flex;gap:10px;margin:15px 0;"> <img src="https://via.placeholder.com/100/FF5733" style="width:100px; height:100px;"> <img src="https://via.placeholder.com/100/FF5733" style="width:100px; height:100px; filter:brightness(150%) saturate(200%) hue-rotate(90deg);"> </div>

## Color Schemes

### Popular Palettes

#### Material Design
**Colors**: `#FF5252`, `#FF4081`, `#E040FB`, `#7C4DFF`, `#536DFE`
**Preview**:
<div style="display:flex; height:30px;">
   <div style="flex:1; background:#FF5252;"></div>
   <div style="flex:1; background:#FF4081;"></div>
   <div style="flex:1; background:#E040FB;"></div>
   <div style="flex:1; background:#7C4DFF;"></div>
   <div style="flex:1; background:#536DFE;"></div>
</div>

**Code**:

```
<div style="display:flex; height:30px;">
   <div style="flex:1; background:#FF5252;"></div>
   <div style="flex:1; background:#FF4081;"></div>
   <div style="flex:1; background:#E040FB;"></div>
   <div style="flex:1; background:#7C4DFF;"></div>
   <div style="flex:1; background:#536DFE;"></div>
</div>
```

#### Pastel
**Colors**: `#FFD3B6`, `#FFAAA5`, `#FF8B94`, `#A8E6CF`, `#DCEDC1`
**Preview**:
<div style="display:flex; height:30px;">
   <div style="flex:1; background:#FFD3B6;"></div>
   <div style="flex:1; background:#FFAAA5;"></div>
   <div style="flex:1; background:#FF8B94;"></div>
   <div style="flex:1; background:#A8E6CF;"></div>
   <div style="flex:1; background:#DCEDC1;"></div>
</div>

**Code**:

```
<div style="display:flex; height:30px;">
   <div style="flex:1; background:#FFD3B6;"></div>
   <div style="flex:1; background:#FFAAA5;"></div>
   <div style="flex:1; background:#FF8B94;"></div>
   <div style="flex:1; background:#A8E6CF;"></div>
   <div style="flex:1; background:#DCEDC1;"></div>
</div>
```

#### Dark Mode
**Colors**: `#121212`, `#1E1E1E`, `#2D2D2D`, `#3E3E3E`, `#4F4F4F`
**Preview**:
<div style="display:flex; height:30px;">
   <div style="flex:1; background:#121212;"></div>
   <div style="flex:1; background:#1E1E1E;"></div>
   <div style="flex:1; background:#2D2D2D;"></div>
   <div style="flex:1; background:#3E3E3E;"></div>
   <div style="flex:1; background:#4F4F4F;"></div>
</div>

**Code**:

```
<div style="display:flex; height:30px;">
   <div style="flex:1; background:#121212;"></div>
   <div style="flex:1; background:#1E1E1E;"></div>
   <div style="flex:1; background:#2D2D2D;"></div>
   <div style="flex:1; background:#3E3E3E;"></div>
   <div style="flex:1; background:#4F4F4F;"></div>
</div>
```

## CSS Variables

```
:root {
  --primary: #6200ee;
  --primary-dark: #3700b3;
  --secondary: #03dac6;
  --error: #b00020;
}

.button {
  background-color: var(--primary);
  color: white;
}

.button:hover {
  background-color: var(--primary-dark);
}
```

## System Colors

```
background: ButtonFace;
color: LinkText;
border-color: ActiveBorder;
```
Supported values: Canvas, CanvasText, LinkText, VisitedText, ActiveText, ButtonFace, ButtonText, etc.

## Resources

- [Color Tools](https://colorhunt.co/)
- [Gradient Generator](https://cssgradient.io/)
- [Contrast Checker](https://webaim.org/resources/contrastchecker/)

# Advanced Color Styles Reference

This reference includes various color formats and styling techniques.

## Color Formats

| Format         | Example                      | Preview |
|----------------|------------------------------|---------|
| HEX            | `#FF5733`                    | <div style="background-color:#FF5733; width:60px; height:25px;"></div> |
| RGB            | `rgb(255, 87, 51)`           | <div style="background-color:rgb(255, 87, 51); width:60px; height:25px;"></div> |
| RGBA           | `rgba(255, 87, 51, 0.7)`     | <div style="background-color:rgba(255, 87, 51, 0.7); width:60px; height:25px;"></div> |
| HSL            | `hsl(12, 100%, 60%)`         | <div style="background-color:hsl(12, 100%, 60%); width:60px; height:25px;"></div> |
| HSLA           | `hsla(12, 100%, 60%, 0.5)`   | <div style="background-color:hsla(12, 100%, 60%, 0.5); width:60px; height:25px;"></div> |
| Named Color    | `coral`                      | <div style="background-color:coral; width:60px; height:25px;"></div> |

## Gradient Examples

| Type               | CSS Code | Preview |
|--------------------|----------|---------|
| Linear Gradient    | `background: linear-gradient(to right, #ff9a9e, #fad0c4)` | <div style="background: linear-gradient(to right, #ff9a9e, #fad0c4); width:150px; height:25px;"></div> |
| Diagonal Gradient  | `background: linear-gradient(45deg, #a1c4fd, #c2e9fb)` | <div style="background: linear-gradient(45deg, #a1c4fd, #c2e9fb); width:150px; height:25px;"></div> |
| Radial Gradient    | `background: radial-gradient(circle, #ffecd2, #fcb69f)` | <div style="background: radial-gradient(circle, #ffecd2, #fcb69f); width:150px; height:25px;"></div> |
| Rainbow Gradient   | `background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet)` | <div style="background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet); width:150px; height:25px;"></div> |

## Color Effects

| Effect              | CSS Code | Preview |
|---------------------|----------|---------|
| Text Shadow         | `text-shadow: 2px 2px 4px rgba(0,0,0,0.5)` | <div style="text-shadow: 2px 2px 4px rgba(0,0,0,0.5); padding:10px;">Shadow Text</div> |
| Box Shadow          | `box-shadow: 5px 5px 15px rgba(0,0,0,0.3)` | <div style="box-shadow: 5px 5px 15px rgba(0,0,0,0.3); width:80px; height:30px; background:#4CAF50; margin:10px;"></div> |
| Blend Mode          | `background-blend-mode: multiply` | <div style="width:80px; height:30px; background: linear-gradient(to right, #FF416C, #FF4B2B), url('data:image/svg+xml;utf8,<svg xmlns=\"http://www.w3.org/2000/svg\"><rect width=\"100%\" height=\"100%\" fill=\"%2300BCD4\"/></svg>'); background-blend-mode: multiply; margin:10px;"></div> |
| Opacity             | `opacity: 0.7` | <div style="opacity:0.7; background:#FF5722; width:80px; height:30px; margin:10px;"></div> |

## Popular Color Schemes

### Monochromatic
<div style="display:flex; gap:5px;">
  <div style="background:#003366; width:30px; height:30px;"></div>
  <div style="background:#336699; width:30px; height:30px;"></div>
  <div style="background:#6699CC; width:30px; height:30px;"></div>
  <div style="background:#99CCFF; width:30px; height:30px;"></div>
</div>

```
background: #003366;  /* Dark blue */
background: #336699;  /* Medium blue */
background: #6699CC;  /* Light blue */
background: #99CCFF;  /* Very light blue */
```