---
assignees:
- mj
- adonese

---


GeoidApp is a [software application for various geoid computations](https://docs.google.com/presentation/d/1PQPQbFPC6srIOTjAVAOpScWsvsr5a3KtvOW7I118T6M/edit?usp=sharing). It can run in your machine, or in your phone, or even in the browser.

With GeoidApp you can:

 - Git rid of the costs of all those costs regarding the instruments, workers, etc.
 - We help you to scale. Don't worry, the price is still fixed.
 - It's even affordable for students.

Our goal is to replace the old expensive surveying methods with a new cheap method.

#### GeoidApp is:

* **portable**: It can run on your pc, phone, cloud you name it.
* **fully-supported**: By our strong community, comprehensive documentation. We even plan on making a few videos.

The GeoidApp project was started as our graduation project in 2015. We have a few modification for the core of the project, mostly because we want to make as generic as possible.

##### Ready to [Get Started](/docs/getting-started-guides/)?

## Why GeoidApp?

We will be looking quite deep into some physical, mathematical aspects.

Let's define our problem, and then we shall discus various ways to tackle it. Finally we will compare our approach with the other approaches.

#### Figure of the earth

##### The classical (conservative) approach of modeling the earth

People have had different theories about the shape of the earth. While now, you can easily believe that the earth has some sort of sphere (spheroid for the 3D) shape. Well, that wasn't the case earlier. Because back then people were limited to a few distances, it was intuitive to say that it's a flat body. For a very long time it was accepted that the earth is a sphere, and there were nice experiments behind this theory [See Eratothenes].
They latest theory of the figure of the earth was proposed by Newton (as a theory), and proved by other guy (I forgot his name, conveniently). They propose to use the ellipsoid as a surface the represents the earth. They basically said that the earth can't be a sphere due to it's rotation around the sun. Gauss suggested to use the geoid as a shape of the earth. While they keep to use the ellipsoid as an approximation for the geoid. Ellipsoid has the advantage of having a simple mathematical model, compared to irrregular surface, the geoid.
All of the previous mentioned methods share the a common feature. They are all rely on terrestrial observation to model the earth.

##### The modern approach of modeling the earth

The modern approach was proposed by Molodnskey in 60's. Molodnskey has argued that we can model the earth without to worry about the physical components --those requires the terrestrial measurements, hence the time consumption, and cost. With this theory we can obtain some parameter from dedicated satellite missions for the gravity observation (see GOCE), and model the earth with respect to them.

Summary of GeoidApp:

There are many advantages of GeoidApp, both in terms of the theory, and in terms of the practical consideration.

* **Customization**
It was crafted to fit your very own use case.
* **Less-touch**
You need only to enter the least number of commands, literally just the area you want to compute their geoid height values, and we will do the hard work for you.
* **Efficiency**
Our application is built on top of C/C++ highly optimized algebra routines to make sure that we have the best software in terms of efficiency. But because languages like C/C++ or FORTRAN are hard to work with for non-developers, we made a very simple interface to work with the back-end of the software. In particular we have front-end of MATLAB, Java, and soon we will add a support for JS.

#### Why do I need to use GeoidApp

* It's intended to replace the GPS. While the GPS can accurately measure the latitude and the longitude, but its height is not the one the related to the geoid. You just can't use the the height derived from GPS directly in surveying works.




#### GeoidApp is not intended to:

In places with very complicated topography structure e.g. mountains.
