# Infrared on Digital Cameras
## Includes some .cube LUTs and presets to use with the filter feature on Nothing Camera
> Examples courtesy of Mathieu Stern from YouTube, dj9kw.de & Rob Shea Photography

<img width="1136" height="639" alt="autochrome-look1" src="https://github.com/user-attachments/assets/7923bf65-eb0c-40d5-8261-1dd3263cc897" />


> Infrared light sits just beyond the visible red portion of the electromagnetic spectrum, typically between 700nm and 1,000nm. While invisible to the human eye, camera sensors are inherently sensitive to it. Manufacturers block it using an IR-cut filter to maintain accurate color reproduction.
> 
> **Note:** I’m still *very* new to infrared photography, this writeup is based on what I’ve learned so far in such a short period of time and what I found fascinating enough to document. Some details are surely inaccurate or incomplete. So, if you spot mistakes or have insights to share, I’d genuinely appreciate your corrections or advice, all I want is to keep learning and improving my understanding of how to use infrared effectively.

## Motive
I’ve always wanted to try infrared photography. I’d seen countless surreal, otherworldly images over the years and wanted to understand what made them so captivating. I wanted to create something similar myself but the deeper I looked into it, the more I realized how expensive it can be to get started with. Especially if you’re trying to do it the traditional way with film.

True IR photography reveals glowing foliage, unique interactions of light with water and haze, and subtle textures like veins in leaves or skin. The colors and contrasts arise naturally from the way infrared light behaves with everything it touches. This produces effects that no amount of editing can truly replicate. It’s approachable to fake, but the depth and nuance of real infrared remain out of reach without shooting in-camera.

Unfortunately, without access to infrared film or the ability to modify a camera, I am forced to start with post-processing. Trying to emulate the look using regular visible-spectrum RAW images. It’s nowhere near the real thing, more of a rough imitation than true infrared, but it makes the process far more approachable and opened the door for me to start learning.

## Trying to perform the Mod

This contains what i've learnt from the little time I spent looking up how to do this on the internet.

I have to mention that you might have to practically sacrifice a digital camera for this. You have to remove its built-in IR Filter to convert it into a Full-Spectrum camera. This is the only way to do this.

It's definitely hard to do, and it does carry a risk of ruining your sensor permanently if your hands aren't very delicate. Don't even bother trying if you don't have the right equipment or if you're doing it on the only camera you have. It is not worth it.

[Kolari Vision](https://kolarivision.com) is one of the few companies that does such conversions on cameras. If you want to, you could get it done by a professional, and get a matching set of high-quality filters to start off with.

![through_IR_block](https://github.com/user-attachments/assets/c7210228-233c-43cd-b369-fb579d335787)

Here's what you'll basically be doing. You have to start by removing the factory IR Filter on the camera, then replace it with a clear pane of glass.

There's many YouTube videos on this so you can check [here](https://www.youtube.com/results?search_query=infrared%20conversion%20on%20a%20digital%20camera), or check for guides on [r/infraredphotography](https://www.reddit.com/r/infraredphotography/) at Reddit. Sometimes people there [sell their old gear,](https://www.reddit.com/r/infraredphotography/comments/sv7r8f/buy_and_sell_thread/) so you might find it useful if you've got some cash.

Once you're finally done, you've enabled the sensor to access a much broader spectrum of light: sensitive all the way from UV to the Visible spectrum and up to Infrared. \
Now all you need to do is limit what the sensor can see by placing an appropriate filter ahead of it.

## Fake it till you make it!
A cheap, low-tech solution to replicate the look is to use post-processing on your images or video to achieve the typical infrared image look. This is what i'm trying for now. \
But doing this does mean that your image, while it may look like an infrared image, would nowhere be close to actually being one. You'd just be hue-shifting your colours to emulate a certain look.

This means you fail to capture a large amount of the essence of why infrared images look the way they do. The sensor captures real light and are influenced by physics and the environment they're capturing. You notice the quality in the final output.

## What you might already be familiar with
The most common type of images you would find when looking up an infrared images would be outdoor scenes with all the greenery turned into a blood-red with perfect blue skies, and any water body turned into a bright teal. This is usually emulating the look of Kodak Autochrome films of late.

<img width="1136" height="639" alt="autochrome-look2" src="https://github.com/user-attachments/assets/9d865c6d-b742-4060-a381-6e26393f8a43" />


Or perhaps you might find images of light pink vegetation and baby blue skies, a look that makes the world look like it's made of candy floss. This is done by channel-inverting a 720nm filter. 

<img width="1509" height="849" alt="720nm-channelswap" src="https://github.com/user-attachments/assets/8a460f42-75ac-4178-9da2-23e992ff781e" />


This filter in its default state with no processing produces very desaturated, almost ghostly monochrome images, with barely blue vegetation and pale yellow skies.

 <img width="1509" height="849" alt="720nm-stock" src="https://github.com/user-attachments/assets/4e202db8-d73f-46dc-8083-f119289e6801" />

## A common list of Infrared filters and their effects

| Filter (nm) | Typical Look / Effect |
|--------------|-----------------------|
| **550nm** | Shows a colour palette with strong false colors and vivid yellow-blue contrast. |
| **590nm** | Warm, glowing foliage under deep cyan skies. Ideal for rich color shifts. |
| **665nm** | Balanced tones with typically red-gold foliage and moderate sky contrast. |
| **720nm** | The classic infrared look, bright white vegetation and near-black skies. |
| **760nm** | Softer contrast and muted tones, leaning toward gentle monochrome. |
| **850nm** | Deep, dramatic black-and-white with pronounced foliage luminosity. |
| **950nm** | Pure infrared capture; stark monochrome and extremely high contrast. |
| **Full Spectrum (UV–IR)** | Records ultraviolet through to infrared; relies on external filters for control. |

> **Note:** As wavelength increases, visible light is progressively blocked. Colors fade, contrast rises, and images shift toward pure monochrome.

Achieving proper white balance in IR photography can be tricky. Most cameras struggle to auto-balance infrared light. I've heard setting a custom white balance using green foliage under sunlight often yields the best results.

Shooting video in infrared introduces some especially unique visual properties you can explore: skin tones appear porcelain-like, fabrics behave unpredictably, and skies can sometimes turn ink-dark.

Of course this is just the tip of the iceberg when it comes to cool grading we can achieve with infrared. With some time you can pull off really freaky, almost alien feeling imagery. This has been attempted on commercial cinema before already with terrific results.

<img width="1374" height="950" alt="color-treatments_rob-shea" src="https://github.com/user-attachments/assets/cfbf59c2-25d9-4fda-8555-4162d8044c47" />

https://github.com/user-attachments/assets/aebb2fa1-f3df-4a45-b51b-0ae0603ef185

## A word of caution

Infrared imaging doesn’t just capture pretty colors; it often reveals light that’s invisible to the human eye. This opens the door to both creative and concerning implications.

When working with full-spectrum or infrared-converted cameras, you’re essentially bypassing one of the safety mechanisms built into modern imaging systems: the IR-block filter. That means your sensor, and by extension your lens, now sees everything that reflects or emits infrared light. While that’s what makes the images so magical, it also means you can sometimes see things that weren’t meant to be visible.

Infrared photography can see beneath certain surfaces in subtle ways. It can reveal the texture of fabrics, the pattern of subdermal veins, and sometimes even details beneath thin layers of clothing or makeup under the right lighting conditions. While this property is fascinating for artistic or scientific use, it’s also incredibly invasive.

Be extremely cautious and respectful when photographing people, even if your intention is purely creative. It’s possible to unintentionally capture revealing or private details that wouldn’t be visible under normal light. Always ask for consent when shooting people using infrared, and **NEVER** use modified cameras in public spaces where individuals haven’t agreed to be photographed.
