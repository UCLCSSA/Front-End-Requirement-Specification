# UCLCSSA WeChat App Frontend Requirement Specification

## Terminology

This specification uses the terms **MUST, SHOULD, MAY, MUST NOT, MAY NOT, SHOULD
NOT, RECOMMENDED, OPTIONAL, REQUIRED** as defined in [RFC2119](https://tools.ietf.org/html/rfc2119).

## Backend Requirement

### Post Page

#### Post Block Detail
| Parameter  |    Format            |    Remarks          |
|:----------:|:--------------------:|:-------------------:|
|Title       |                      |                     |
|Brief Text  |                      |                     |
|Pictures    |                      |                     |
|User Name   |    FelixH            |                     |
|Post Date   |    2019-2-3          |                     |
|Post Time   |     15:17            |                     |

#### Post Page Display    
- First 4 Articles  

Each time user swipe to the end of the page, resend the next 4 articles.

### Main Page  

#### Weather and Date  

| Parameter      |    Format            |    Remarks          |
|:-------------: |:--------------------:|:-------------------:|
|Weather         |  Sunny               |                     |
|Date            |  2019-2-3            |                     |
|Suggest Dressing|  Shirt               |                     |
|temperature     |  23 - 31 (℃)         |                     |
  

#### Events  

- Pictures  
- Title  

#### Personal Timetable Block  

| Parameter     |    Format            |    Remarks          |
|:-------------:|:--------------------:|:-------------------:|
|Start/End Time |  16:00 - 18:00       |                     |
|Lecture Type   |  Lecture             |                     |
|Lecture Name   |  Logic               |                     |
|Lecture Hall   |  JB Canteen          |                     |
|Professor Name |  Felix Vldimear      |                     |


#### Library Seats

| Parameter     |    Format            |    Remarks          |
|:-------------:|:--------------------:|:-------------------:|
|Library        |  Science Library     |                     |
|Number of seat |  234 left            |                     |

 
### Restaurant Page  

#### Restaruant Block Detail  

| Parameter     |    Format            |    Remarks          |
|:-------------:|:--------------------:|:-------------------:|
|Payment Type(s)| Cash/Card            |  Cash,Card,Alipay   |
|Restaurant Name| Wasabi               |                     |
|Distance       | 230 m                | From main library   |
|Suggestion     | Exit from north gate |                     |
|Food Type      | Japanese             |                     |
|Favorable Rate | 75%                  |                     | 
|Location       | Warren Street 300    | From google map api |
 