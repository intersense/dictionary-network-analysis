# Dictionary Network Analysis

## A Digital Humanities Research Case

- Tangut Dictionary 《文海》*Wenhai*
- OPTED Open Plain Text English Dictionary

## 《文海》Wenhai 
- wenhai_gephi.csv
    - 可以直接使用Gephi打开，本数据表只有两列：source，target
    - 本文件中的四位数字是西夏字的字典序号，如果希望在Gephi中显示西夏文，可以与作者联系。
- 可视化

<img src='https://github.com/intersense/dictionary-network-analysis/blob/main/images/%E5%9B%BE1.jpg' width='300px'/>

<img src='https://github.com/intersense/dictionary-network-analysis/blob/main/images/%E5%9B%BE3.jpg' width='300px'/>

<img src='https://github.com/intersense/dictionary-network-analysis/blob/main/images/%E5%9B%BE4.jpg' width='300px'/>

注意：Jupyter Notebook中可能会因为没有安装西夏文字体而导致部分文本无法显示，但由于csv文件中已经删除西夏字，且代码也进行了调整，因此运行过程应该不会有问题。

## OPTED 
The largest SCC of OPTED: {'popovtsy', 'dukhobors', 'dukhobortsy', 'judaizers', 'bezpopovtsy', 'molokane', 'skoptsy', 'raskolnik', 'molokany', 'raskolniki'}

- Prompt：Please use these words to tell a story：popovtsy, dukhobors, dukhobortsy, judaizers, bezpopovtsy, molokane, skoptsy, raskolnik, molokany, raskolniki.
- Answer:
In the vast expanse of the Russian Empire, a tapestry of diverse religious sects and movements wove through the lives of its people, each with its unique beliefs and practices. Among these were the Popovtsy, Dukhobors, Dukhobortsy, Judaizers, Bezpopovtsy, Molokane, Skoptsy, and Raskolniki. The Popovtsy were a faction of the Old Believers who retained a priesthood and traditional liturgical practices. They believed in the preservation of the old rituals and were often in conflict with the state church, which had reformed certain practices that the Popovtsy considered sacred. In contrast, the Bezpopovtsy were another group of Old Believers who rejected the need for priests altogether, believing that the priesthood had been corrupted. They held their own services and maintained a strict adherence to what they saw as the true faith, without the mediation of clergy. The Dukhobors, also known as Dukhobortsy, were a pacifist Christian sect that rejected the Russian Orthodox Church's rituals and hierarchy. They believed in the inner light of Christ and communal living, which often put them at odds with the authorities. Their commitment to pacifism and communal life led them to migrate to Canada in the late 19th century to escape persecution. The Molokane were another sect that sought to return to the simplicity of early Christianity. Rejecting the Orthodox Church's rituals, they emphasized the reading of the Bible and the guidance of the Holy Spirit. The Molokany, a subgroup of the Molokane, were known for their refusal to recognize civil authority or take oaths, which often brought them into conflict with the state. The Skoptsy were a radical sect that practiced castration, believing it was a way to purify themselves and prepare for the coming of Christ. Their extreme practices led to severe persecution by the state, and they were often forced to live in isolated communities. The Judaizers were a group that adopted some Jewish customs and beliefs, rejecting the divinity of Jesus and the Orthodox Church's teachings. This movement was seen as heretical by the Orthodox Church, leading to harsh crackdowns on its followers. Finally, the Raskolniki were a general term for the Old Believers who split from the Russian Orthodox Church after the reforms of Patriarch Nikon in the 17th century. This schism, or raskol, created a wide array of sects, including the Popovtsy and Bezpopovtsy, each with its own interpretation of the true faith. These groups, with their diverse beliefs and practices, painted a picture of a society in religious flux, each seeking to find their own path to spiritual truth amidst the pressures of an often hostile state and dominant church. Their stories are a testament to the enduring human spirit and the quest for religious freedom and authenticity.

- Prompt:请将上文翻译为中文。
- Answer：在广袤的俄罗斯帝国内,各种不同的宗教派别和运动穿梭于人们的生活之中,每一个都有其独特的信仰和实践。其中包括波波夫兹、杜霍波尔人、杜霍博尔兹、犹太教徒、别兹波波夫兹、莫洛坎人、斯科普兹和拉斯科尔尼基。波波夫兹是旧信徒派系中保留祭司制度和传统礼仪实践的一支。他们相信保持古老的仪式,常常与改革了某些他们认为神圣的做法的国家教会发生冲突。相比之下,别兹波波夫兹是另一个旧信徒群体,他们完全拒绝祭司的需要,认为祭司制度已经腐败。他们举行自己的礼拜,严格遵守他们所认为的真正的信仰,没有神职人员的调解。杜霍波尔人,也被称为杜霍博尔兹,是一个信奉和平主义的基督教派别,他们拒绝俄罗斯东正教会的仪式和等级制度。他们相信基督内在的光明,以及集体生活,这常常使他们与当局发生对抗。他们对和平主义和集体生活的承诺,导致他们在19世纪末迁徙到加拿大,逃避迫害。莫洛坎人是另一个寻求回归早期基督教简单性的教派。他们拒绝东正教会的仪式,强调阅读圣经和圣灵的指引。莫洛坎人,莫洛坎人的一个支派,以拒绝承认公民当局或宣誓而闻名,这常常使他们与国家发生冲突。斯科普兹是一个实行阉割的激进派别,他们相信这是净化自己,为基督的再临做准备的一种方式。他们极端的做法导致国家的严厉迫害,他们常常被迫生活在偏远的社区。犹太教徒是一个采用一些犹太习俗和信仰的群体,拒绝耶稣的神性和东正教会的教义。这一运动被东正教会视为异端,导致其追随者遭受严厉打压。最后,拉斯科尔尼基是一个笼统的术语,指的是在17世纪尼康牧首改革后从俄罗斯东正教会分裂出来的旧信徒。这种分裂,或拉斯科尔,创造了各种各样的派别,包括波波夫兹和别兹波波夫兹,每一个都有自己对真正信仰的解释。这些群体,凭借其多样的信仰和实践,描绘了一个宗教动荡的社会图景,每个人都在寻求找到通往精神真理的自己的道路,同时还要面对常常充满敌意的国家和主导教会的压力。他们的故事见证了人类精神的持久力量,以及对宗教自由和真实性的追求。
