## GLSE 中的数据类型

| 类型  | 描述                       |
| ----- | -------------------------- |
| float | 表示浮点数                 |
| vec4  | 表示由四个浮点数组成的矢量 |

## 顶点着色器中的内置变量

| 类型  | 变量名       | 描述                 | 备注        |
| ----- | ------------ | -------------------- | ----------- |
| vec4  | gl_Position  | 表示顶点的位置       | 必须赋值    |
| float | gl_PointSize | 表示点的尺寸（像素） | 默认值：1.0 |

## 片元着色器的内置变量

| 类型 | 变量名       | 描述                     | 备注 |
| ---- | ------------ | ------------------------ | ---- |
| vec4 | gl_FragColor | 指定片元颜色（rgba格式） |      |

### 两角和公式![两角和公式](https://bkimg.cdn.bcebos.com/pic/8644ebf81a4c510f085ead476259252dd52aa5d1?x-bce-process=image/resize,m_lfit,w_268,limit_1/format,f_jpg)

