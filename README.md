# TencentHomeWorkFinal
第一人称局域网射击游戏
一、实现功能

1、游戏大厅

  （1）输入名字后可选择单人/多人模式，单人模式直接进入地图。
  
  （2）选择多人模式后可以选择创建或者加入房间，之后进入等待大厅
  
  （3）大厅可等待玩家进入，并选择人物，仅房主可以切换地图（但都只做了一个人物和地图所以换不了），之后房主可以开始游戏，进入loading界面，加载完毕后进入地图
    
  
 2、战斗对局
 
 （1）进入地图后会显示十秒倒计时，当倒计时结束时开始刷怪
 
 （2）怪物被杀光或一定时间后会继续刷新怪物直到本关所有怪物都刷新完毕
 
 （3）当怪物全数死亡且守护物存活则胜利，若在这之前守护物死亡或者玩家复活次数耗尽则游戏结束
 
 3、主角相关
 
  （1）主角空手开局，可以捡掉落的武器
 
  （2）主角可以拾取buff道具以及消耗道具，目前buff道具为加速和加攻击力的两种，消耗道具为回复生命值的回复道具（按3使用）
 
  （3）主角UI界面包含小地图，玩家信息（血量，名字，buff，复活次数，头像），武器状况，得分
      
  （4）主角死亡后模拟布娃娃状态，并在数秒后复活，并扣除复活次数

  
  4、枪械相关
  
  （1）两种武器，步枪和火箭筒，步枪是射中造成伤害，而火箭筒是爆炸造成伤害
  
  （2）两种武器均可开镜
  
  5.命中规则
  
  （1）近战攻击（拳头，武器）命中后扣血
  
  （2）远程武器攻击命中不同位置会造成不同伤害，使用物理材质实现
  
  6、怪物相关
  
  （1）怪物有两种类型，远程和近战，两者运行不同的行为树有不同的行动逻辑
  （2）怪物会攻击守护物，若看到玩家则优先攻击玩家
  （3）AI具备寻路功能
  
  6、其他
  
  （1）掉落：不同怪物死亡后掉落物不同，均有概率掉落buff道具和消耗道具，近战怪物会掉落近战武器，远程怪物会掉落远程武器
  （2）道具：含增加攻击力，增加移速，回血道具
  
  
  二、演示视频
