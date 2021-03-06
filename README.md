<img src="http://i.imgur.com/DrI3FkN.png" width="200">

# Cytoid <a href='https://play.google.com/store/apps/details?id=me.tigerhix.cytoid&hl=en'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' width="100"/></a><a href='https://itunes.apple.com/us/app/cytoid/id1266582726?ls=1&mt=8'><img alt='Download on the App Store' src='https://devimages-cdn.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store.svg' width="100"/></a>

 [中文说明请按这里](https://github.com/TigerHix/Cytoid/blob/master/README_cn.md)

> A community version of the rhythm game Cytus.

**Cytoid** is an open-source alternative to the rhythm game [Cytus](https://www.rayark.com/g/cytus/).

*Visit the level database: [CytoidIO](http://cytoid.io/browse).*

# Backstory

Cytus is argubly one of the best rhythm games on a mobile device. While the game is both visually and audibly impressive, it is a shame that the game does not allow user customization like [osu!](https://osu.ppy.sh). Since many years ago, the Cytus community has been constantly finding ways to contribute fanmade content; from [chapter mockups](https://www.youtube.com/watch?v=84Gefg5YdYg&t=453s), [charts](https://www.youtube.com/results?search_query=Cytus+fanmade) to tools like [Cytunity](http://cytus-fanon.wikia.com/wiki/User_blog:JCEXE/List_of_Cytus_simulation_programs:_2017_edition#Cytunity) (a popular chart editor) and [GLCytus](https://github.com/Dewott/GLCytus) (a simulator that looks almost identical to the original game). However, the former ones are often for ornamental purposes only; while the latter ones are, although powerful and can create [amazing results](https://www.youtube.com/watch?v=2sopAxd8MZ0), often too advanced for the normal user. There are also ways to mod the game, but those are way too complicated and probably not legal things to do.

With the release of the [sequel](https://www.youtube.com/watch?v=rAStr9pjq_A) around the corner, and the fact that Cytus has not been receiving updates for almost a year now, it feels about time for the community to step up and extend the original gameplay together, by encourging all people to create, share and play original fanmade content. *"But modding the game is illegal!"* That's why I present to you Cytoid, a cross-platform Unity game, offering:

* Fully functional Cytus-like gameplay
* Original visuals and sound fx
* Easy import of custom levels
* A touchscreen-friendly chart editor **(WIP)**

Which means, accordingly:

* (To players) You don't have to sit there and watch fanmade charts; you can now outright play 'em!
* (To developers) No need to worry about copyright issues anymore!
* (To chart makers) Test out your charts on devices to ensure they are feasible!
* (To all) Make your very first chart without getting into unnecessary technical issues! **(WIP)**

<img src="http://i.imgur.com/QkCV1IW.png" width="800">
<img src="http://i.imgur.com/ueIS1Eo.png" width="800">
<img src="http://i.imgur.com/zJ7rp2D.png" width="800">
<img src="http://i.imgur.com/oFquEC5.png" width="800">
<img src="http://i.imgur.com/uqvBSf5.png" width="800">
<img src="http://i.imgur.com/UoqjWit.png" width="800">

## Getting Started (For Players)

Cytoid is a community-driven rhythm game; although it comes with a [tutorial level](http://cytoid.io/browse/io.cytoid.glow_dance), it depends on the community - or you - to create and share new levels. [CytoidDB](http://cytoid.io/browse) is a good place to start if you are finding new levels to play.

If you are a charter, please head to the [wiki](https://github.com/TigerHix/Cytoid/wiki/a.-Creating-a-level) for information on creating a Cytoid level, or converting a Cytus custom chart into a Cytoid level (spoiler: no effort needed).

## Getting Started (For Developers)

This project is developed in [Unity](https://unity3d.com/). A rough decision in fact, but comparing to [libgdx](https://libgdx.badlogicgames.com/) which I used in my previous [Cytus simulator project](https://github.com/TigerHix/Pulmusic), Unity allows me to iterate the development process much faster for [many reasons](https://gamedev.stackexchange.com/a/8133). The downside is Unity does not work great when it comes to version control and team collaboration, and [GitHub for Unity](https://unity.github.com/) does not seem to work well by now. If you want to contribute in this project, shoot me an e-mail or open an issue so we can get things started.

As of latest version, Cytoid requires following paid/free assets in the project in order to build:

- [DOTween](https://www.assetstore.unity3d.com/en/#!/content/27676), free
- [DoozyUI](https://www.assetstore.unity3d.com/en/#!/content/47352), $50
- [JsonDotNet](https://www.assetstore.unity3d.com/en/#!/content/11347), $25
- [LeanTouch](https://www.assetstore.unity3d.com/en/#!/content/30111), free
- [LunarConsole](https://github.com/SpaceMadness/lunar-unity-console), free
- [Simple UI - Scroll View Extensions](https://www.assetstore.unity3d.com/en/#!/content/93873), $15
- [TextMesh Pro](https://www.assetstore.unity3d.com/en/#!/content/84126), free
- [XCode API](https://bitbucket.org/Unity-Technologies/xcodeapi/src/), free

Because of license restrictions, it is impossible to include these assets in this repository. Please manually install them by using Unity's built-in Asset Store.

Refer to [#20](https://github.com/TigerHix/Cytoid/issues/20) for more information.

## Release History

* 1.1
    * Fix severe performance issue
* 1.0
    * First public release
    * Bug fixes
* Beta 2
    * Import of `.cytoidlevel` files
    * Bug fixes
* Beta 1
    * It's working!

## License

Source code (unless stated otherwise) is distributed under [MIT](https://opensource.org/licenses/MIT) license. See `LICENSE` for more information.

`Glow Dance` by [iamMANOLIS](http://iammanolis.com/) is licensed under [CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/).

## Meta

Proudly presented by [Tiger Tang](https://github.com/tigerhix/).
* Twitter: [@tigerhixtang](https://twitter.com/tigerhixtang)
* Email: [tigerhix@gmail.com](mailto://tigerhix@gmail.com)

Special thanks to [xuxu9110](http://xuxu9110.github.io/) for his incredible charts.

And finally,
```
Long Live the Rayark
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMM;``````````````````OMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMM8```````````````MM;``````````````NMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMM``````````````````MMMM``````````````````MMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMM`````````````````````8MMMMM;```````````````````'MMMMMMMMMMMMMMMM
MMMMMMMMMMMMMM``````````````````````MMMMMMMM``````````````````````MMMMMMMMMMMMMM
MMMMMMMMMMMM```````````````````````;MMMMMMMMM'``````````````````````MMMMMMMMMMMM
MMMMMMMMMM````````````````````````MMMMMMMMMMMM````````````````````````MMMMMMMMMM
MMMMMMMM'````````````````````````OMMMMMMMM`'MMM;```````````````````````OMMMMMMMM
MMMMMMM8````````````````````````8MMMMMMMM```;MMM````````````````````````MMMMMMMM
MMMMMM;````````````````````````'MMMMMMMM``````MMM'MMMMMMMMMN`````````````8MMMMMM
MMMMMM````````````````````````NMMMMMMM`NO;`````NMM`OMMMMMMMMMMM```````````MMMMMM
MMMMM8``````````````'8MMO;````MMMMMMM```````````MMM'```OMMMMMMM```````````8MMMMM
MMMMM'``````````````````````OMMMMMMM``````````````MM```'MMMMM8````````````;MMMMM
MMMMM'`````````````````````'MMMMMM`````````````````MM'MMMMM8``````````````;MMMMM
MMMMM8````````````````````'MMMMMM```````````````````MMMMM;````````````````8MMMMM
MMMMMM````````````````````MMMMMN`````````````````8MMMM`;``````````````````MMMMMM
MMMMMMO`````````````````;MMMMM````````````````MMMMM````M`````````````````NMMMMMM
MMMMMMM;````````````````MMMMM``````````````MMMMN````````M'``````````````8MMMMMMM
MMMMMMMM;`````````````'MMMMO```````````MMMM8`````````````8`````````````8MMMMMMMM
MMMMMMMMMM````````````MMMM``````````````````MMMN``````````;'``````````MMMMMMMMMM
MMMMMMMMMMMM`````````MMMM```````````````````````;MM'````````````````MMMMMMMMMMMM
MMMMMMMMMMMMMM``````MMM;``````````````````````````````M;`````'````MMMMMMMMMMMMMM
MMMMMMMMMMMMMMMM;``MMM`````````````````````````````````````````;MMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMN```````````````````````````````````````OMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMM````````````````````````````````MMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMM8'````````````````;NMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
```
