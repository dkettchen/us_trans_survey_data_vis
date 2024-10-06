## Visualising and analysing US Trans Survey Data

Learning plotly.py by visualising some percentage data taken from the [2015 and 2022 US Transgender Surveys](https://ustranssurvey.org/).

### Here are the results

The sample group was significantly larger (more than tripling from 27,715 in 2015 to 92,329 in 2022) in the 2022 survey, yet the percentages largely remained similar.

Trans women are still more common than trans men, in spite of lower overall amab numbers, while afab nonbinaries still vastly outnumber amab ones. Crossdressers remain in the vast minority as well.
![alt text](vis_testing/total_survey_gender_distribution.png)

Trans women's lead over trans men's numbers has increased noticeably.
![alt text](vis_testing/total_survey_binary_distr.png)

Overall, we still have an afab majority among the general trans population, although this has slightly improved (likely due to the increase in trans women's/decrease in trans men's percentages).
![alt text](vis_testing/total_survey_direction_distribution.png)

Supposing that an equal amount of either birthsex *is* (medically speaking) transgender, and in the knowledge that detransitioners who detransition due to legitimately not being trans after all are a dismissibly small minority,

> 2015 USTS Chapter 7 Section C on detransition outlines that only 8% of respondants reported ever having detransitionned, of which only 5% (that is 0.4% of total respondants) reported that their reason for detransition was that "They realized that gender transition was not for them" (while 62% (about 5 out of those 8%) reported that they were currently living in a gender role other than their birth-assigned one).

it seems unlikely that it would be cis women mistakenly labelling themselves as transmascs causing this discrepency. 

Therefore we can instead suppose that amab trans people still feel less able to come out as trans and seek the transition (social and medical) they need than afab ones.

### Nonbinary numbers

Among the nonbinary participants, afab nonbinaries remain in the vast majority, making up roughly 4/5 of the community.
![alt text](vis_testing/total_survey_nb_distr.png)

Around the time of the first survey, the reigning theory in the community (source: me, who came out as NB in 2014) for why there were less amab nonbinaries than afab ones was that it was due to lack of nonbinary awareness among amab people. That -given time and awareness raising for nonbinary as a concept in wider society- that number would balance out eventually and we would have a roughly equal amount of amab and afab NBs, the same as trans men and women were roughly balanced.

*TURNS OUT THIS WAS INCORRECT.*

Despite an increase in the community's numbers at large due to more awareness and the pandemic forcing people to sit with themselves (= current reigning theories in the community) (source: me, who (as just one example) attended Trans Pride Brighton in 2019 and 2022 and can attest to a *significant* increase in attendance between the two events.) as well as in the sample size of the 2022 survey, the percentage of amab nonbinaries has remained almost stagnant in these 7 years of trans and nb awareness raising.
![alt text](vis_testing/survey_nb_distr.png)

What change there has been has been a slight increase to all identities other than trans men and crossdressers, who lost percentages, trans men's percentage being hit the hardest with a 4 percent point drop.
![alt text](vis_testing/survey_gender_distr_comp.png)

<!-- I believe this is a sign that:

- <ins>The amab/afab nonbinary split is caused by things other than trans/nonbinary awareness, such as people's ability to pass and gender roles.</ins>

    Supposing that the motivations behind any trans person's journey and need for change are equally balanced between birth assignments, the only difference between transmascs & transfemmes should be the direction of their transition, and the social implications thereof.

    - Ease of passing:

        A first puberty on estrogen and testosterone have different effects. Estrogen holds back the development of pretty much all aspects other than breast tissue and hip size, while testosterone grows everything other than those two things. 
        
        Bones cannot be changed after reaching adulthood, so transmascs tend to struggle with underdevelopped features (compared to cis men) and transfemmes with overgrown ones (compared to cis women), like their height or facial features.

        This leads to a lot of adult transmascs being misaged as teen boys even if they do manage to pass as male. (source: have some ND Stevenson comics: like [this one](https://substack.com/@gingerhaze/p-135215962), or [this one](https://substack.com/@gingerhaze/p-138118385))

        Transfemmes may be demonised and hounded by transphobes for their body size but they are at least recognisable as adults regardless of assumed gender.

        Also amab people dressing in women's clothes are less normalised than the reverse, leading to people being more likely to recognise even a pre-med transfemme as such than an equivalent transmasc.

        &rarr; Therefore transfemmes have an easier time being recognised as adult women than transmascs have being recognised as adult men.

        That is not to say it's impossible for transmascs to pass (or super easy for transfemmes), but it seems to take the average transmasc longer/further into medical transition to start passing securely. (source: me, who it took literally a decade, 5+ years of HRT, several surgeries, and finally a complete and utter commitment to masc presentation to pass as male about 95% of the time (still not always 🙃) as opposed to being misgendered as a cis woman every day of the prior *decade* of my out then-nb-identified life.)
    
        One of my main reasons for presenting femme & sticking to the nb label for as long as I did was that I couldn't pass even if I tried back then, and I was scared of getting misaged even if I did, so, unable to access the option I actually wanted, I chose the role of "woman" over that of "child", to at least be recognised and taken seriously as the grown-ass adult I was.

        I believe people who struggle with passing more take longer to claim a binary label, or are more likely to maintain their nonbinary label. (Ex. ND Stevenson still identifies as bigender despite coming out as Nate he/him boy and pursuing masculinising medical transition.)

        Nonbinary labels offer a space to openly be a work in progress and fulfill gender needs (dressing a certain way, accessing medical transition, etc) without having to complete a full binary social transition or otherwise explain yourself.
    
    - Gender roles:

        Afab people face less pressure to stay women, leading to more trans-identified afab people than trans-identified amab people overall. 

        If the female gender role doesn't work for them they can easily claim the nonbinary label, because matriarchy doesn't consider you a defector unless you Are A Man. It retains control and influence because it doesn't fully cut people off until they reach patriarchy's gates.

        Transmascs internalise the deep-seated misandry and manhate the female gender role and feminism promote, putting pressure on them to not be men (cause men are bad obviously 🤦‍♂️), leading to more hesitation around claiming manhood, even when they are literally medically pursuing masculinising transition. 

        This leads to the inflated afab nonbinary rate and disproportionally low trans male numbers we see.

        Amab people face more pressure to stay men. Unless it really isn't working for you, you are to stick to the male gender role. 
        
        Patriarchy, unlike matriarchy, worries greatly about defectors and will do whatever it takes to try and prevent escape. This is why there's still proportionally less amab people claiming trans identities than afab people despite more trans awareness. 

        (Crossdressing communities like femboys and drag gaining popularity seems to be mitigating this a bit, as they offer a genderqueer space where male identity and femme expression/bodily looks can coexist and be explored without the need to claim an explicitly trans/nb label to do so.)

        Transfemmes, successfully having escaped, are cut off by the male gender role, leaving little merit in the nonbinary label for them unless they have other reasons to claim it (such as struggling to pass, being cis-leaning, having other stuff to work through first, etc). Additionally womanhood is significantly less stigmatised and more desirable than manhood (gets ya empathy, aesthetics, desirability, and, thanks to feminism, lets ya keep all the stuff from the male gender role too, like jobs, bank accounts, *pants*, etc). 
        
        This leads to the higher rate of trans women we see despite the overall amab minority, and the incredibly low amab nonbinary rate.

- <ins>Nonbinary awareness isn't helping free gender roles.</ins>

    It offers reprieve from them for people who struggle to fit in for various reasons, but because genderqueer people label themselves as nonbinary, withdrawing their membership from either gender role, rather than claiming it, their gender transgressions do not impact binary gender roles as much as they would if they were committing them under those labels. 

    - Ex. An amab or physically masculine looking person wearing a skirt is highly transgressive if they identify as a man, but expected and highly irrelevant to the male gender role if they identify as nonbinary, leaving the male status quo intact. 
    
        If this is a medically transmasculine person or an amab person who genuinely does not plan on physically transitionning, that likely means they could reasonably claim the male label if they wanted to, yet they don't. -->

### Possible causes for these discrepencies

Supposing that inherent reasons for transgenderism of any label and direction are equally balanced in the population between birth assignments, these stark discrepencies must have other explanations.

#### Transmascs and transfemmes move in opposite directions between gender roles.

- More people coming from the female gender role feel able to come out as trans, but less than half of them currently claim the male gender role instead. This points to more freedom to (at least in label) leave the female gender role's domain, but more pressure not to join the male one.

- Less people coming from the male gender role feel able to come out as trans, but the vast majority of those who do claim the female gender role instead. This points to more pressure to (at least in label) stick to the male gender role, but more incentive to join the female one once you've left it.

This is likely the consequence of the past century of feminism improving the female gender role and stigmatising the male one by promoting manhate and misandry. 

- The male gender role has not been liberated, leading to narrower standards and more pressure, and girls are indoctrinated to hate men, disincentivising transmascs from claiming the male label, even if they're literally accessing masculinising medical treatment. By keeping the nonbinary label they can exist outside of the female gender role without having to commit to the male gender role and all its downsides.

- Meanwhile the female gender role brings perks like empathy, aesthetics, desirability, as well as all the perks previously reserved for the male gender role, like jobs, bank accounts, *pants*, etc, leaving little merit in keeping the nonbinary label for transfemmes. Boys are taught to be allies to feminism lest they would be a horrible person, so transfemmes will also be significantly less prejudiced against the female gender role than transmascs against the male one.

<!-- 
Besides the increase in general trans awareness, crossdressing communities like femboys and drag gaining popularity seem to be mitigating the effects of the pressure to stay in the male gender role a bit, as they offer a genderqueer space where male identity and femme expression/bodily looks can coexist and be explored without the need to claim an explicitly trans/nb label to do so. 

- We can already see this in the slight increase in the transfemme percentage.
    
- And while the crossdresser percentage has decreased from 3% to 2%, this is still a massive increase in participation numbers along with the total, pointing to crossdressing still playing a relevant role in the trans community even with more trans awareness. (If it was a completely niche and outdated concept to be skipped over in a more trans-aware world, presumably that percent would've decreased significantly more.)

- Transfemmes crossdressing before coming out as trans is a well-known phenomenon. (source: any transfemme drag queen, like Bosco or Gigi Goode; various trans women in the public eye, like most recently Harper Steele in the "Will & Harper" (2024) documentary, speaking of their crossdressing past) -->

#### They differ in how their bodies and presentation influence passing.

Their bodies developped differently from their cis peers in first puberty, and no matter how much medical transition one undergoes, certain things are harder to change than others and bones for example can't be changed at all (with the exception of *some* facial bones (which is prohibitively expensive and nearly unprecedented for transmascs (source: me, who's had FMS))) after finishing first puberty.

- Estrogen holds back a lot of features while testosterone overgrows them, leading to a lot of transmascs struggling to pass as the correct age even if they pass as male. (source: have some ND Stevenson comics: like [this one](https://substack.com/@gingerhaze/p-135215962), or [this one](https://substack.com/@gingerhaze/p-138118385))

Furthermore women and afab people wearing men's clothes is more normalised than men and amab people wearing women's clothes, leading to transfemmes being more easily identified as not cis than transmascs.

This means that transfemmes have an easier time passing as adult women sooner in their transition, than transmascs do passing as adult men. (source: me, who it took literally a decade, 5+ years of HRT, several surgeries, and finally a complete and utter commitment to masc presentation to pass as male about 95% of the time (still not always 🙃).)

- I can't speak for every last transmasc, but at least for me that was one of the main reasons to stick to the nonbinary label for as long as I did. 

    Passing as what I wanted (the adult non-woman I am) was not an option, so I chose to present in a way that would get me misgendered as an adult woman who would at least be respected as such, rather than misaged as a child and not be treated as an adult (and still risk misgendering anyway). 

    And in absence of the physical reality necessary to call myself a man without feeling like it was a demonstrable lie, nonbinary was the only option for me to be able to cope and access the medical treatment I needed.

    I suspect there are many others in similar positions.

#### Finally due to their different directions & circumstances, there are cultural differences between genderqueer amab & afab people.

I believe that crossdressing in the widest sense (drag, fetish crossdressing, crossdressing in private, theatrical crossdressing, femboys, crossplay (cosplay version), crossplay (video game/digital version)) fulfills a similar exploratory role for amab people that claiming the nonbinary or other queer labels plays for afab ones. (source: transfemme drag queens (like Gigi Goode or Bosco), well-known trans women talking about crossdressing before coming out as trans (like most recently Harper Steele in the documentary "Will & Harper" (2024)), [the prevalence of anime girl avatars in VRchat](https://www.youtube.com/watch?v=5v_Dl7i4Bcw), [femboys who end up coming out as transfemme/accessing medical transition](https://youtu.be/3reFDwM0yIA?si=LcqWDL16hgayxTAb), etc - it is a very well-known phenomenon in relation to the transfemme community at large)

However, in spite of its inclusion in this survey, crossdressing is colloquially generally not considered part of the trans community in the same way nonbinary labels are, meaning crossdressers would've been less likely to respond to a survey aimed specifically at the transgender community.

A lot of crossdressing is also treated less as an identity/something to come out as than nonbinary labels, or happens in private to begin with, so less crossdressers would be "out as" such or consider it a core part of their gender identity as opposed to more of a practice/hobby/preference/etc.

I believe this has led to their numbers being vastly underrepresented in this dataset. 

- I do not think that genderqueer amab people are actually that much less likely to explore and transgress gender than afab ones, I believe it's merely that they are less able to do so publicly and less likely to consider it an identity in its own right the way butch and nonbinary afab people do.

- If we look at crossdresser communities like drag etc, we see a similarly (if not more) unbalanced ratio between high numbers of amab people and low numbers of afab people as we do the other way around in our nonbinary numbers. (f.e. between RuPaul's Drag Race and Dragula, we've (to my understanding) only seen 2 afab performers (one of which was a hyperqueen -> not doing crossdressing drag) on the latter, with the entire rest of the cast across 16+ seasons of drag race and 5 seasons of dragula being amab (which is a much, much smaller minority than the 1/5 amab nonbinaries we see in our data set here).)

### Conclusion

I believe that, between the prevalence of misaging and misgendering for transmascs, internalised misandry and the stigma and limitations of the male gender role, a lot of trans men/strongly trans-male-aligned people are currently still labelling themselves as nonbinary instead of claiming the male label, 
and that, between gender role pressures, limited opportunity for exploration for amab people, and the underrepresentation in this particular dataset of the crossdressing communities fulfilling that role, we are still missing a lot more transfemmes that have yet to come out and/or label their genderqueer identity as such.

As gender lib progress happens and people progress in their exploration and transitions, I hope to see these numbers balance out, including nonbinary afab numbers finally decreasing, instead joining the trans male block, and amab overall numbers continuing to increase.

#### Change

One thing to keep in mind with this community is that it is defined by change. Not merely in the sense of transition, but across the board. Our labels, attitudes, choices and needs can change over time. We learn things about ourselves, we conceptualise ourselves differently, and the world sees us differently. 

Even the most binary of transitions is not a binary switch like that wording may imply, it is an arduous, messy, time-consuming process. Genderqueer spaces like crossdressing or the nonbinary label are means for people to cope with that. 

Studies like these, while incredibly insightful, can only ever track the current usage of labels by fluctuating subsets of the community, not the actual truth that lies underneath them, and we need to keep that in mind when analysing their data. 

These scewed numbers do not indicate that inexplicably afab people are more likely to *be* nonbinary, or the only amab people who come out are trans women and the missing percent of trans guys just won't come out for some reason. 

They indicate that amab and afab people use labels differently, even when they are experiencing the same phenomenon (in this case that of transgenderism and genderqueerness). 

And I want my community to finally grapple with that.