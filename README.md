[简介](#简介)
<br/>
[系统](#系统)

<h2>简介</h2>
> 本项目拟在基于三国时期的背景做一个类似大富翁类的战棋类游戏，通过投掷骰子在地图上按照指定的路径循环漫游。沿路径会有城池或者第三方地点，玩家可以占领城池和守卫自己的城池或者在第三方地点遭遇新事件。在漫游的过程中会获得各种成就和经验还有特殊物品奖励，当然最后的胜利也与之挂钩。

<h2>系统</h2>
> 1. [城池系统](#城池系统)
> 2. [武将系统](#武将系统)
> 3. [攻防系统](#攻防系统)
> 4. [物品系统](#物品系统)
> 5. [事件系统](#时间系统)
> 6. [玩家系统](#玩家系统)
> 7. [成就系统](#成就系统)
> 8. [骰子系统](#骰子系统)

<h3>城池系统</h3>
>* 建设：直接挂钩的是城池外观的豪华程度，升级城池的建设会增加人口上限（每个城池只能有一定百分比以内的士兵数）、农业指数上限和商业指数上限。农业指数直接影响每回合增长的粮食数量，商业上限直接影响每回合增长的金钱数量，人口数量会影响每回合粮食数量的消耗。
>* 农业：发展农业会增加农业指数，农业指数上限和城池建设等级有关。产生的粮食供每回合消耗以及战争消耗。
>* 商业：发展商业会增加商业指数，商业指数上限和城池建设等级有关。产生的金钱用来征兵和招募武将和购买装备，也可以用来兑换粮食。
>* 军事：包括征兵、招募武将、分配士兵、处理战俘。可征兵的数量和人口数量和金钱数量有直接关系，至于武将，对于每一个武将都有城池的等级限制以及玩家的成就值，对于分配士兵，需要根据武将的属性来分配，详见武将系统，对于战俘可以花金钱来招降，或者直接斩了，斩了之后战俘身上的装备归城池所有。
>* 其他：包括治理城池、搜寻城池、掠夺城池、分配装备和各种间谍行为等其他行为。治理城池是为了解决城池的非正常状态，比如洪水，饥荒，暴乱等；搜寻城池可以搜出少量粮食和金钱以及隐藏武将或物品；掠夺城池可以掠夺出大量金钱和粮食，但是会大量降低城池的各种属性，不利于可持续发展；分配装备是将城池里的各种装备分配给武将，从而提升属性和忠诚度（留给间谍行为利用）。

