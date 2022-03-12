## 九点圆定理

# I. 内容:

- $\triangle ABC$的三边中点$D、E、F$，三个高足$I、J、K$，垂心和顶点的连线的中点$X、Y、Z$,九个点共圆

该定理有以下四个推论

1. 九点圆的圆心$V$是外心和垂心所连线段的中点,九点圆的半径是三角形外接圆半径的一半;
   
   ![0.png](./img/0.png)

> 证明:在$\triangle ABC$中，垂心是$H$,外心是$O$,连接线段$AH$,
> 又作$BC$的中点$M$,连接$OM$,故$OM \perp BC$,(垂径定理)
> 连接$AO\cap OH$于$G$,下面证明$G$是重心
> (思路:让$OM$成为中位线并把$AH$转移)
> 作$BD \perp BC$于$B$,连接$CD$,$AD$.
> 只需证$AHBH$是平行四边形，导角(因为$\triangle AIC \backsim \triangle BJC$)可以证明$AH\parallel DB$且$AH=DB$
> 所以$OM$平行且等于$\frac{1}{2}BC$
> 所以$\frac{MG}{GA}=\frac{OM}{AH}=\frac{1}{2}$
> 根据重心的相关判定和性质，可以得知$G$为$\triangle ABC$的重心
> 一个三角形的重心、垂心、内心共线，这就是**欧拉线定理**
>  ![1.png](./img/1.png)

然后我们证明原定理

> 作$AH$的中点$X$,连接$XM$,交$OH$于$V$,易证$\triangle VHX \cong \triangle VOM$
> 显然$V$是$OH$的中点(当然，也可以用$V$是$OH$的中点推出$\triangle VHX \cong \triangle VOM$)
> 所以$VM=VX$,又因为$\triangle MIX$是直角三角形,
> 所以$VM=VI=VH$,所以$V$是$\triangle MIX$的外接圆，也是$\triangle ABC$的九点园
>  ![2.png](./img/2.png)
> 原命题得证

2. 垂心组$A、B、C、H$的四个三角形$\triangle ABC、\triangle ABH、\triangle BCH、\triangle CAH$有共同的九点圆,因此$\triangle ABC$的九点园实际上是垂心组$A、B、C、H$的九点圆.所以上面四个三角形半径相等;

   > 因为垂心和顶点连线的中点是其他垂心组三角形的中点，所以该定理显然

3. $\triangle ABC$的九点圆和$\triangle ABC$的外接圆是外位似形，位似中心是$H$,位似比是$1:2$而且它们又是内位似形，位似中心是$G$,位似比也是$1:2$;
- 首先看外位似:
  ![3.png](./img/3.png)

  > 由$XY$是$AB$的中位线知道$XY$平行且等于$\frac{1}{2}AB$
  > (对称的得到其他2组:$YZ$平行且等于$\frac{1}{2}BC$,$ZX$平行且等于$\frac{1}{2}CA$)
  > 所以$\triangle XYZ$位似于$\triangle ABC$，且位似比例是1:2.

- 再看内位似：
  ![4.png](./img/4.png)

  > 由$DE$是$BC$的中位线知道$DE$平行且等于$\frac{1}{2}BC$
  > (对称的得到其他2组:$DE$平行且等于$\frac{1}{2}AB$,$FD$平行且等于$\frac{1}{2}CA$)
  > 所以$\triangle DEF$位似于$\triangle ABC$，且位似比例是1:2.
4. 三角形的外心$O$、重心$G$、九点圆圆心$V$、垂心$H$这四点，有$\frac{OG}{GH}=\frac{1}{2}$,$\frac{GV}{VH}=\frac{1}{3}$即$GH$调和分割线段$OV$

   > 根据1的性质，显然证明出$\frac{OV}{VH}=1,\frac{OG}{GH}=\frac{1}{2}$
   > 然后有$\frac{GV}{VH}={1}{3}$
   > 所以有$\frac{OG}{GV}=\frac{OH}{HV}=2:1$
   > 原命题得证
