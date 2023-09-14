# Report 3 - Week of 09/07 - 09/14

# Hello! 🌟 Welcome to my weekly report!

This week, I mainly focused on Project 1: Computational Design. I [redesigned the cell phone stand](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/blob/main/weekly%20report/Report%203%20-%20Week%20of%2009%2007%20-%20%2009%2014.md#redesign-the-cell-phone-stand) based on my preferences; [product features](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/blob/main/weekly%20report/Report%203%20-%20Week%20of%2009%2007%20-%20%2009%2014.md#product-features) are listed here. And I created a [progress video](https://youtu.be/6hY8ILsYISs) to record what I did and learned. The personal [reflection and speculations](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/blob/main/weekly%20report/Report%203%20-%20Week%20of%2009%2007%20-%20%2009%2014.md#reflections) can be found here.


## *Redesign the cell phone stand*

At the beginning of the week, I decided to redesign the model instead of continuing to work on last week's model, as I redefined my challenges and design goals, while the original model was too limiting to work on.

As I reflected on my daily life, I noticed two common scenarios where I use a cell phone stand: FaceTiming with my family and friends and watching videos while eating. 
![scenario 1](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/34252547-2b5c-432b-9aeb-d8938f6278ae)
_FaceTime with my family and friends_
![scenario 2](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/99d11d6b-893f-46fb-bdcf-329839746238)
_watch videos while eating_

Based on user journey analysis, problems of the current cell phone stand are listed here.
- **The angle of use is fixed and cannot be adapted to flexible environments.**
- **The aesthetic consideration of the product is lacking and there is no product semantics.**
- **The cell phone holder is too bulky and not easy to carry.**

To solve these problems, I brainstormed some concepts and made further design choices. I decided to give the product a semantic meaning by designing a chair for the phone. I did some quick sketches to define the shape and form. I chose a simple design style, using cylinders and cuboids. 

<img width="400" alt="sketch 1" src="https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/22a8eeff-528c-4e60-9853-5eed9959b694">
<img width="400" alt="sketch 2" src="https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/c935fb7d-a7a7-4e3a-aabb-fee7bbd24e2f">

Then, I used Rhino and Grasshopper to create a 3D model, incorporating boolean operations to create the hole and shaft structure. 1 mm tolerance was set to ensure effortless assembly.

<img width="1449" alt="modeling in grasshopper" src="https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/a1fe0e04-5b62-4e64-8bc2-88a3d475f7bc">

Once the design was finalized, I exported the parts to STL files.

<img width="280" alt="stl file top" src="https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/2e39f109-2767-45bb-ab72-73635dd48274">
<img width="280" alt="stl file support" src="https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/548b7229-e2b5-477d-bfa1-c8c2cd92b158">
<img width="280" alt="stl file base" src="https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/b300a8c7-694b-444f-9b33-ec4e408a3cf5">

Then I configured the Prusa 3D printer using CURA. I optimized the part placement to minimize material use.

<img width="1000" alt="Screenshot 2023-09-14 at 3 37 17 PM" src="https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/69dd694e-811b-44e6-bc13-6e2061f5c912">

Before printing, I double-checked the nozzle’s temperature.

![check nozzle temperature](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/6068e15f-e59e-4f07-970b-9767f9a38d24)

Finally, I obtained the finished parts, cleaned everything up, and assembled the stand.
![IMG_4125](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/62e0c0e5-2820-4bd2-9df9-8b428d433e41)

![3d printed product](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/cff33317-3276-4941-9ad0-d5294f6e446b)


## *Product features*
In this section, detailed product features are introduced.

- **Suitable for different using scenarios**
The stand can accommodate both portrait and landscape orientations.
![portrait stand](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/728ad486-ecd0-42fa-95da-87c1a0ae9ff4)
![landscape stand](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/7b684ba1-4985-4671-b9dd-cdf423fc1fae)

- **Adjustable**
It offers flexibility for different seating heights by allowing adjustments for the most suitable viewing angle through various slots.
![angle 3](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/ddfebc13-a955-4b0c-989e-fe7ccfd74038)
![angle 2](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/07d3aa3b-2a3d-48d7-b9cc-2468e3a26ae0)
![angle 1](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/64ada8bb-d913-4710-85cf-128267ebe867)

- **Portable**
It's designed to be easily disassembled and assembled for increased portability. 
![IMG_4195](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/de8c3505-820e-48ac-8572-6bcb5160dfc6)

- **Playful**
The chair-shaped stand adds a touch of joy to its functionality
![stand with kaka](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/1a466830-f6a5-448c-8cac-4e868c23a00e)
![stand with airpords pro](https://github.com/Berkeley-MDes/tdf-fa23-Yukihan528/assets/143134371/ec6aaaff-23f5-43f7-bbd7-7d331e1dfc23)

## *Progress video*
Please find my progress video via this link. https://youtu.be/6hY8ILsYISs

## *Reflections and speculations*

- I'm happy with this design because it boasts an appealing, cute style and offers an enjoyable user experience while remaining portable and adaptable. It meets my initial design expectations and aligns with the concept of incorporating engaging aesthetics into products, particularly in today's era where psychological well-being is paramount – we need "warm" design.
- However, it's important to acknowledge some limitations. Storage considerations were overlooked, and the loss of one support leg could hinder functionality. Additionally, I failed to incorporate the ability to charge the phone while using the stand, as reflected last week. This aspect could be a potential area for improvement.
- In summary, this design may not be a typical computational design output, but it perfectly caters to my personal preferences. Overall, it was a refreshing experience to work with Grasshopper, and I thoroughly enjoyed the learning journey.
