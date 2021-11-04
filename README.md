# Project-2: Climate Change
Global Warming is demanding a shift to sustainable energy...

 

 
![Introduction](https://user-images.githubusercontent.com/83662813/140378333-f982fdaf-96e0-43cc-884f-867379759419.jpg)

---
   

**Introduction**
 
> So, let's start with the Paris agreement; The Paris agreement is an agreement within the United Nations framework convention on climate change or the UNFCCC dealing with greenhouse gas emissions mitigation adaptation and ﬁnance. The Paris agreement's long-term goal is to keep the increase in global average temperature to well below 2 degrees Celsius above pre-industrial levels and to limit the increase to 1 1/2 degrees Celsius since this would substantially reduce the risks and eﬀects of climate change. 


![conclusion](https://user-images.githubusercontent.com/83662813/140381950-53f15e6a-43f5-4ca6-b963-e0eb90234caa.jpg)
 
 <!-- TABLE OF CONTENTS -->
 <img align="left" src="https://user-images.githubusercontent.com/65415371/124740340-9eb50180-df12-11eb-9295-e33ac2752c57.png" width="50px" />
<h2 id="table-of-contents"> Table of Contents</h2>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#Background"> ➤ Background</a></li>
    <li><a href="#Heat-Map"> ➤ Heat Map</a></li>
    <li><a href="#XGBoost-and-LinRegression"> ➤ XGBoost and LinRegression</a></li>
    <li><a href="#Global-Production-Scatter-plot"> ➤ Global Production Scatter plot</a></li>
    <li><a href="#CO2-Emissions"> ➤ CO2 Emissions</a></li>
    <li><a href="#Total-Energy-Consumption"> ➤ Total Energy Consumption</a></li>
    <li><a href="#Methane-Emission"> ➤ Methane Emission</a></li>
    <li><a href="#The-investment-Choices"> ➤ The investment Choices</a></li>
    <li><a href="about-the-project"> ➤ About The Project</a></li>
    <li><a href="#Prerequisites"> ➤ Prerequisites</a></li>
    <li><a href="#Project-roadmap"> ➤ Project Roadmap</a></li>
    <li>
      <a href="#Deliverables"> ➤ Deliverables</a>
      <ul>
        <li><a href="#Key-Project-Features">Key Project Features</a></li>
      </ul>
    </li>
    <!--<li><a href="#experiments">Experiments</a></li>-->
    <li><a href="#conclusion-and-discussion"> ➤ Conclusion and Discussion</a></li>
    <li><a href="#references"> ➤ References</a></li>
    <li><a href="#contributors"> ➤ Contributors</a></li>
  </ol>
 
  ---
 
 ### Background

![gas-g72ef54a4d_1920](https://user-images.githubusercontent.com/83662813/140406889-84e1f360-d529-4d72-b92b-f7f79008d431.jpg)
 
 
 
 
 
 
 
 
 
 
 ---

 
### Heat Map:

<p align="left"><img width=75% src="https://user-images.githubusercontent.com/83662813/140378691-819e930c-fec2-4c1b-ba3c-971859873efd.jpg"></p>

To achieve the aims of the Paris agreement we're going to have to have zero emissions by 2050, that means we must stop burning fossil fuels. The problem is, we're just nowhere close to that. The United Nations itself in the IPCC special report on global warming of 1.5 degrees Celsius has accepted that there isn't any obvious path to zero emissions in such a short  time frame, because currently globally we admit around 40 billion tons of carbon dioxide a year. So, the United Nations is banking on something called N.E.Ts. N. E. Ts are negative emissions technologies that include things like carbon capture and storage. Basically, you take the carbon dioxide out of the atmosphere and bury it underground, but carbon dioxide isn't the only greenhouse gas and it's not the only problem. There's methane too. Now, methane comes from cows, it’s also released by oil wells and coal mines and it is 84  times more potent of a greenhouse gas than carbon dioxide. Methane is also trapped inside the permafrost, which is melting and releasing more of this gas into the atmosphere. There's nitrous oxide that comes from fertilizer which is 300  times more potent of a greenhouse gas than carbon dioxide and then there's CFC's or chloroﬂuorocarbons which are thousands of  times more potent than carbon dioxide, still in the atmosphere, and they’re not falling as quickly as everybody hoped.

As a result, the problems faced are huge and we have very little   time to remedy it. If we don't do something soon, we're going to see more droughts, we’re going to see crop failure, rising sea levels, more extreme weather events, more climate change refugees, and the outcome is going to be disastrous. Glaciers are melting, sea levels are rising, droughts are more frequent and extreme weather events are more common. This is climate change in action, and you've heard it all before, however a major report was just released on August 9th, 2021, looks at how close we are to this irreversible damage and it's looking disastrous. Back in 2015 the world's leaders came together to solidify a plan to combat climate change, the resulting Paris agreement mentioned earlier, set a goal to hold the increase of global average temperature well below 2 degrees Celsius above pre industrial levels, and add the intent of limiting the temperature increase to 1.5 degrees Celsius but now in August 2021 the UN intergovernmental panel on climate change or the IPCC compiled the results of over 6000 scientiﬁc studies and released a new report. The main takeaway, at our current rate, is that the global average temperature is likely to rise 1.5 degrees Celsius as early as 2030. This means, we only have 9 years to make drastic changes or will miss our target. The diﬀerence between 1.5 and 2 may seem small and it's hard to imagine how half a degree could make much of an impact but using climate models’ scientists can predict what half an increase in temperature means for our planet. And needless to say it means a lot.

 
---   

### XGBoost and LinRegression

<p align="left"><img width=75% src="https://user-images.githubusercontent.com/83662813/140379393-b3680d32-83c3-47a1-9364-21dac7a37c39.jpg"></p>

First there's the arctic, at 1.5 degrees warming Arctic Sea ice will last through most summers but at 2 degrees ice free summers become ten times more likely. This would not only be devastating for Arctic wildlife but would reduce the albedo or the amount of light being reﬂected away from the earth causing even more warming. Ice melt coupled with rising temperatures of 1.5 degrees means sea level rise could be somewhere between 26 and 77 centimeters. At 2 degrees that range could go up a whole 10
centimeters.

That change could expose about 10 million more people to harmful ﬂooding than if warming stays at 1.5. A warmer world also means that fresh water will become even more scarce. At 1.5 degrees, severe drought will likely aﬀect 350 million people but at 2 degrees that number grows to 411 million people. Heat waves get worse too, at 1.5 degrees about 14% of the world's population will be exposed to severe heat waves and at 2 degrees that number more than doubles rising to a Wapping 37%. Then there's the coral reefs, at 1.5 degrees warming 70 to 90% of the coral reefs die, at 2 degrees that number grows to greater than 99%, meaning virtually all coral reefs will disappear. This would be devastating to marine biodiversity and aﬀect nearly 500 million people who rely on them for storm protection, food, jobs and recreation.

 
---  
     
### Global Production Scatter plot

<p align="left"><img width=75% src="https://user-images.githubusercontent.com/83662813/140380462-f9d3806a-7d0e-4c63-a555-2960312dce7c.jpg"></p>

If none of this fazes you, a separate study published in Nature looks at how many people could die from that half a degree rise. They found that due to air pollution alone an additional 150 million people could die if we hit that 2 degree mark, and that's not even including the likely death by heatwave, drought, famine, and other devastating pandemics caused by new diseases. The report makes it clear that the pledges made in the Paris agreement will not be enough, it not only states that these goals won't keep us under the 1.5-degree mark, but that they could result in the warming of three degrees by 2100 a whole degree higher than what the world decided would be the upper threshold.  With the global population increasing, there is the exception of the African region keeping the CO2 emissions at an acceptable level as the temperature increases. It is important to note that the regions measured and plotted are as follows: 
 
African Region: Includes only countries that are geographically located on the con  nent. 
 
Asia Region: Includes only countries that are geographically located in Asia.
 
World Region: Includes countries who do not fall in the previous two categories.

---   
   
### CO2 Emissions 
  
<p align="left"><img width=75% src="https://user-images.githubusercontent.com/83662813/140380661-dadd8056-d899-4e44-a863-e46ad4f93231.jpg"></p>

To prevent this, the report states that we must drastically reduce our CO2 emissions well before 2030 and at a faster rate than we ever have before. While highly unlikely, scientists are stressing that keeping warming to 1.5 degrees is still possible. Projections suggest it would require CO2 emissions to take a nosedive and then operate in the negatives towards the end of the century. While there's no deﬁnitive plan yet, it would likely involve steep across the board investment in renewables. The electriﬁcation of huge energy sectors that currently run-on fossil fuels, and rapid advances in negative emission technologies NETs that could suck carbon out of the air. Among other things like a carbon tax, a worldwide reduction in meat consumption, a decline in popula  on growth, and maximizing global energy eﬃciency.

So yes, it will quite literally take everything we've got, but it is possible. So, what do you think we can do? Negative emission technologies could be a big player in the ﬁght against climate change but how feasible are they?
 
---
   
### Total Energy Consumption

<p align="left"><img width=75% src="https://user-images.githubusercontent.com/83662813/140380798-deba2b4b-4c4e-4c76-97f4-12ccd3dbf278.jpg"></p>

With 40% of global carbon dioxide emissions coming from electricity generation, we can now get a better understanding of what’s happening to the Earth. The 40% is a mixing pot of electricity generation through the combustion of fossil fuels like coal, oil and natural gas necessary to generate the heat needed to power steam driven turbines. The electric grid is set up in such a way that the high voltage transmission towers receive power from coal, hydro and nuclear power. Which is then sent to
distribution centers and then to the end use area such as factories/warehouses, commercial buildings and residential. As shown in the sunburst chart in the presentation file. In 1990 and 1995 the electricity usage is relatively low as the need for electricity compared to today is mostly used as needed. In the year 2000 we saw a big increase in electricity consumption due to the population increasing from 1.6 billion to 6.1 billion people. In 2005 there was a decrease in consumption of electricity and a shift towards smart energy products/machines, as used by many today, with the implementation of smart technologies like energy saving light bulbs, more eﬀective washing machines and dishwashers as a few examples.
 
Yet, even with all these energy saving methods, the increase in global population has continued to increase the demand for eﬃcient technologies. For instance, in the past, cell phones, computers, and the internet which were all considered luxuries have become a way of life for most and show adverse reactions in humans if not a  ainable, proving that our actions and needs drive production and energy demands. Thus the increase in consumption from 2010 to now. This leaves us to emphasize the importance of implementing renewable and sustainable energy sources. The tech industry will continue to grow and hopefully in a positive change will allow us to be more eco-friendly as we advance. 

   
--- 
 
### Methane Emission

<p align="left"><img width=75% src="https://user-images.githubusercontent.com/83662813/140380949-13458dd3-b87b-4a60-b216-9a0de9b47346.jpg"></p>

Currently, there are approximately 1.3 to 1.5 billion cows grazing, sleeping and chewing their curds at any given me on planet earth, and these 1300 pounds are an average weight for both beef and dairy cows. These animals eat a lot. Much like humans when they eat, gas builds up inside of their guts and must be expelled. Cows fart and burp a lot, the result is a large amount of methane being introduced into the atmosphere. In a 2006 UN Food and Agriculture organiza  on report, it claims that the livestock sector, most of which are cows, generates more greenhouse gas emissions as measured in CO2 equivalents and 18% than transport. The average cow produces enough methane per year, to do the same greenhouse damage as four tons of carbon dioxide. So, this signiﬁcantly contributes to global warming. To understand how ca  le produce such high quanties of methane, we need to know that cows, sheep, goats, giraﬀes, and deer belong to a class of mammals called ruminants. Most ruminants have four stomachs and two toed feet. They store their food in the ﬁrst Chamber of the stomach called the rumen before regurgitating it.

This regurgitated food is called curd and the animals chew it again to help further break it down to make it easier to digest. Inside of the rumen, over 400 diﬀerent kinds of microbes exist that also play a critical role in the digestion process. Several of these microbes create methane gas as a by-product. Due to the large number of cows on the planet, along with the large size per cow, they produce more methane gas than all other ruminants combined. This is bad because methane is 21 times more potent at trapping heat from the sun than carbon dioxide. Though it is less prevalent in the atmosphere than carbon dioxide it is by unit one of the most destruc  ve of the greenhouse gases. Since the turn of the 19th century methane gas emissions have increased by 150%. Methane gas like all other greenhouse gases, which includes water vapor, acts as a blanket around our planet trapping heat.

The right amounts and the planet have an average temperature of a life supporting 15 degrees Celsius too little and the greenhouse eﬀect becomes weak like on Mars too much and the surface of the planets becomes so hot it can melt lead like on Venus. Livestock is the largest source of methane gas emissions worldwide, contributing over 28% of total emissions. Wetlands, leaks from oil reﬁneries and drills also contributed methane gas to the atmosphere as well as wildﬁres. In fact, unlike the ratios on a global scale in the United States, livestock is only the third largest contributor behind the mining and
transportation of natural gas and roting landﬁll waste.

It's not as much the farting that's the problem, cows burping, and manure contributed more methane gas than ﬂatulence. According to research at New Zealand’s largest crown Research Institute AG research, up to 95% of the emissions come from the cows’ mouth rather than its behind. It is estimated through whichever oriﬁce that each individual cow lets out between 30 and 50 gallons of methane per day. With an estimated 1.3 to 1.5 billion castles in the world today this adds up fast. As the sunburst plot indicates, the large volume of methane being emitted comes from Australia and the Oceania regions which have a suitable climate to livestock grazing and ranching, including beef cattle, dairy cattle,
domestic deer and most importantly, sheep. Sheep outnumber people in New Zealand by about 12 to 1.

   
---
 
 ### The investment Choices
 
 <p align="left"><img width=75% src="https://user-images.githubusercontent.com/83662813/140381230-f0150edb-9752-4a2b-a659-9b4ed795ef07.jpg"></p>
 
The daily returns plots here of the much-recommended N. E. Ts. (Negative Emission Technologies) compared with a fossil fuel giant shows that we as a human race, pardon the generaliza  on, still maintain conﬁdence in the use of fossil fuels as an energy source, except for Tesla which we can all place at the feet of a need for proﬁt rather than a need to invest in negative energy. The Exxon stocks continue to outperform the clean energy stocks in 2021 and that has the experts believing that the catastrophes impacting the world thus far have done little to curb our mindset.

 ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ABOUT THE PROJECT -->
 <img align="left" src="https://user-images.githubusercontent.com/65415371/124739629-f43cde80-df11-11eb-9033-c5d1d7194f03.png" width="50px" />
<h2 id="about-the-project"> About The Project</h2>
 
 <p align="justify">
  
   
 ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
  
<!-- PREREQUISITES -->
<img align="left" src="https://user-images.githubusercontent.com/65415371/124740780-04a18900-df13-11eb-8a53-ad66e031b55f.png" width="50px" />
<h2 id="prerequisites"> Prerequisites</h2>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) <br>
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) <br>

<!--This project is written in Python programming language. <br>-->
The following open source packages are used in this project:
* Numpy
* Pandas
* Matplotlib
* Python
* XGBoost
* lin Regression
 
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ROADMAP -->
 <img align="left" src="https://user-images.githubusercontent.com/65415371/124739746-10d91680-df12-11eb-86cd-9aa9494e01bd.png" width="50px" />
<h2 id="roadmap"> Roadmap</h2>
 
 <p align="justify">
  
  * 
  * 
  * 
  * 
  
 ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<!-- DELIVERABLES -->
 <img align="left" src="https://user-images.githubusercontent.com/65415371/124741011-3581be00-df13-11eb-8d9a-b44e6fe248a8.png" width="50px" />
<h2 id="deliverables"> Deliverables</h2>
 
 <p align="justify">
  
  **Heaat Map**
 
  
 **Metane Emmission Plot**
 
  
**Temperature Effect of Production**

  
**CO2 emmission per region**
  
  
 ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
 
 

<!-- KEY PROJECT FEATURES -->
 <img align="left" src="https://user-images.githubusercontent.com/65415371/124739888-2cdcb800-df12-11eb-8952-5be64764a7aa.png" width="50px" />
<h2 id="key-project-features"> Key Project Features</h2>

1. Scatter Plots showing methane emmission per global region.
 
2. XGBoost and Lin Regression Models used to predict rising sea levels.
 
3. The rise in temeperatures effect on the world maize, rice and wheat production. 
 
4. The shift or lack thereof from fossil fuels to sustainable energy sources.
 
5. Heat maps showing an increase in temeperature over the last 50 years.
 
6. The Use of electricity and alternative energy sources
 
7. Investment trends indicating human behavior
 
8. The ipcc report on climate change with an emthasis on the climate's temature increase to 1.5 degrees above pre-industrial levels.

9. Countries taking strides to lower their carbon emmisons by 2030
 
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CONCLUSION AND DISCUSSION -->
<img align="left" src="https://user-images.githubusercontent.com/65415371/124740181-74634400-df12-11eb-929c-9aa1bf060806.png" width="50px" />
<h2 id="conclusion-and-discussion"> Conclusion and Discussion</h2>

<p align="justify">
 
As a group Ameera and I embarked on this project because we thought it to be essential that we learn this material and share, so as many people as possible understand what's going on. All the indicators that we have are in the danger zone. We've got increasing Arctic temperatures, we've got rapidly melting sea ice, reduced Arctic reﬂectivity and we've got methane released from permafrost coupled with methane being released from production and cattle grazing. All these indicators are going to lead to enormous problems in a very short amount of time and so, what we want to do is give you some idea of where we are, and what can be done. We thought one of the best things that individuals can do is to inform themselves about exactly what's going on. If you inform yourself, which is something that we are trying to do here, you could understand it better and you can make better decisions. I do hope we have succeeded.

Despite all the issues which combats the planet, we investigated human behavior on a ﬁnancial scale, more speciﬁcally their investment strategies and conﬁdence in the reports and warnings being peppered out. We thought it necessary to portray the conﬁdence in the stock market with regards to our willingness to change and save our planet as a result.


 
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- REFERENCES -->
<img align="left" src="https://user-images.githubusercontent.com/65415371/124740898-1b47e000-df13-11eb-9518-037652dceeb8.png" width="50px" />
<h2 id="references"> References</h2>
 
 <p align="justify">
  
 * 
 * 
 * 
 * 
 * 
 * 
 * 
 * 
  
 ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CONTRIBUTORS -->
<img align="left" src="https://user-images.githubusercontent.com/65415371/124740842-108d4b00-df13-11eb-99f7-c36edc39b2a0.png" width="50px" />
<h2 id="contributors"> Contributors</h2>


 
Group Members: *** Keith Louis, Ameera Gafoor ***

 
 <img src="https://user-images.githubusercontent.com/83662813/137408618-204b30ae-a83f-4a28-b10f-aa60ef66343e.png" align="center"
   alt="bank logo by Keith Louis" width="420" height="250">
 
