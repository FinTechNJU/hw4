# 作业四实验报告
运行模式为伪分布

# 代码解释

## 1. wordcount.java

运行命令
```
wordcount <in> <out>
```

## 2. MatrixMultiply.java

```
运行命令：MatrixMultiply <inputPathM> <inputPathN> <outputPath>
```
## 3. 关系代数

### （1）Selection.java

```
运行命令：Selection <columnname> <symbol> <value> <inputpath> <outputpath>
```

### （2）Projection.java

```
运行命令：projection <columnname> <inputpath> <outputpath>
```
### （3）Unionion.java

```
运行命令：Unionion <inputrelation1> <inputrelation2> <outputpath>
```
### （4）Intersection.java

交运算处理方法类似与并运算
map<line,1>,reduce合并键值对，输出所有<key,2>的key值即可
```
运行命令：intersection <inputrelation1> <inputrelation2> <outputpath>
```
### （5）Difference.java
```
运行命令：Difference <inputrelation1> <inputrelation2> <outputpath>
```
### （6）NaturalJoin.java
```
运行命令：naturaljoin <inputrelation1> <inputrelation2> <outputpath>
```
