# all-about-cam
 <h2 align="center">I am not a robot <img src = "https://media0.giphy.com/media/KDDpcKigbfFpnejZs6/giphy.gif?cid=ecf05e47oy6f4zjs8g1qoiystc56cu7r9tb8a1fe76e05oty&rid=giphy.gif" width = 100px, align="center"></h2>

```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"ā”  I'm passionate about coding and human languages",
		"š­ Iām currently studying a Master's in Business Analytics",
		"š± Iām currently learning Python, R, C++ and Java",
		"šÆ Iām looking to collaborate on Python/finance related projects",
		"š¤ Iām looking for help with anything related to what I am currently learning š",
		"š¬ Ask me about finance and statistical analysis",
		"š« How to reach me at http://linkedin.com/in/cam-perez,
	}
}
```
  
