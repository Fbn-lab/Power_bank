(语言 language) : [CN](https://github.com/fBn0523/Power_bank/blob/main/README.md)|[EN](https://github.com/fBn0523/Power_bank/blob/main/README_EN.md)
# Power_bank
创意设计可乐形状的充电宝\
体积:65直径x116高(mm)\
方案: bm3451电池保护芯片+ip2368充电宝soc(5串18650带均衡)
# 参数

     快充协议:   FCP AFC SCP DPR Try.SRC PD3 QC2 QC3 QC3+(具体以手册为准)
     电压挡位:   5V 9V 12V 15V 20V
     输入:        最大60w 20V3A (双导热管)
                  最大40w 20V2A (无导热管)
     输出:         60W最大20V 3A
     充电指示灯:     (具体根据自己选用的指示灯颜色)
                          放电:                     充电:
                          白 100%~66%               充满 白
                          黄白 66%~33%              100%~66% 白闪
                          黄 小于33%                66%~33%  黄白闪
                          黄闪后结束输出 0%
 

# 特性
      1. 双铜管散热
      2. 保护板控制板叠层设计紧凑内部空间
      3. 可拆卸锂电池仓.方便更换电芯
      4. 60W快充,平衡容量和充电速度.1时20分即可充满
# 制造可行性

      1. 所有零件均可以使用fdm  3d打印制造
      2. 优化电路板减少手工焊接短路风险
      3. 开源文件包含pcb焊接示意图,方便查看每个零件需要焊接的位置
      4. 使用5节亿纬锂能3300mah 18650电芯.整体造价100(人民币)左右
      5. 外壳需要使用两个330ml可口可乐罐,切割工具需自备
# 图片
![image](https://github.com/fBn0523/Power_bank/blob/main/images/img1.JPG) ![image](https://github.com/Fbn-lab/Power_bank/blob/main/images/img4.jpg)
