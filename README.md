# Patika.dev Url
[https://app.patika.dev/mordulu](url)

# Proje 3

##  [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

---

## 1-) Root 7 seçtiğimizde 5<7 olduğundan 5 root'un soluna gider.


|       |       |       | **7** |       |       |   |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-:|
|       |       | **5** |       |  |       |   |

## 2-) 1<7 olduğundan 1, root'un soluna, 1<5 olduğu için 5'in de soluna gider.

|       |       |       | **7** |       |       |   |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-:|
|       |       | **5** |       |  |       |   |
|       | **1** |       |  |       | |   |

## 3-) 8>7 olduğundan 8, root'un sağına gider.

|       |       |       | **7** |       |       |   |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-:|
|       |       | **5** |       | **8** |       |   |
|       | **1** |       |  |       |  |   |

## 4-) 3<7 olduğundan 3, root'un soluna, 3<5 olduğundan 5'in de soluna, 3>1 olduğu için de 1'in sağına gider.

|       |       |       | **7** |       |       |   |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-:|
|       |       | **5** |       | **8** |       |   |
|       | **1** |       |  |       |  |   |
|  |       | **3** |       |       |       |   |

## 5-)  6<7 olduğundan 6, root'un soluna, 6>5 olduğundan 5'in sağına gider.

|       |       |       | **7** |       |       |   |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-:|
|       |       | **5** |       | **8** |       |   |
|       | **1** |       | **6** |       |  |   |
|  |       | **3** |       |       |       |   |

## 6-) 0<7 olduğundan 0, root'un soluna, 0<5 olduğundan 5'in de soluna, 0<1 olduğu için 1'in de soluna gider.

|       |       |       | **7** |       |       |   |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-:|
|       |       | **5** |       | **8** |       |   |
|       | **1** |       | **6** |       |  |   |
| **0** |       | **3** |       |       |       |   |

## 7-) 9>7 olduğundan 9, root'un sağına, 9>8 olduğu için 8'in de sağına gider.

|       |       |       | **7** |       |       |   |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-:|
|       |       | **5** |       | **8** |       |   |
|       | **1** |       | **6** |       | **9** |   |
| **0** |       | **3** |       |       |       |   |

## 8-) 4<7 olduğundan 4, root'un soluna, 4<5 olduğundan 5'in de soluna, 4>1 olduğundan 1'in sağına, 4>3 olduğundan 3'ün de sağına gider.

|       |       |       | **7** |       |       |   |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-:|
|       |       | **5** |       | **8** |       |   |
|       | **1** |       | **6** |       | **9** |   |
| **0** |       | **3** |       |       |       |   |
|       |  |       | **4** |       |       |   |


## 9-) 2<7 olduğundan 2, root'un soluna, 2<5 olduğundan 5'in de soluna, 2>1 olduğundan 1'in sağına, 2<3 olduğundan 3'ün soluna gider

|       |       |       | **7** |       |       |   |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-:|
|       |       | **5** |       | **8** |       |   |
|       | **1** |       | **6** |       | **9** |   |
| **0** |       | **3** |       |       |       |   |
|       | **2** |       | **4** |       |       |   |



# [Patika.dev](www.patika.dev)