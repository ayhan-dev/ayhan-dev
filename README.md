![waving](https://capsule-render.vercel.app/api?type=waving&height=90&color=gradient)

<h2 align="center">👋 Hi, I’m Ayhan-G.Y ♪ </h2> 

![](https://github.com/ayhan-dev/ayhan-dev/blob/main/header.png) 


```

<?php
class Ayhan {
  public $name;
  public $age;
  public $education;
  public $skills;
  public $interests;
  public $account;

  function __construct($name, $age, $education, $skills, $interests, $account) {
    $this->name        = $name;
    $this->age         = $age;
    $this->education   = $education;
    $this->skills      = $skills;
    $this->interests   = $interests;
    $this->account     = $account;
  }
}

class AyhanGaraBay extends Ayhan {
  function __construct() {
    parent::__construct(
      "Ayhan GaraBay", 20,
      "software engineering",
      array("Web", "Network and security", "application","Ai"),
      array("Php", "Python", "Cpp","and ...."),
      array("t.me/Ayhan_dev","ayhan.gy.dev@gmail.com")
    );
    $this->interests = array("Cat developer", "Security specialist");
    $this->future_goals = "My ayhan GaraBay, fullstack developer / Sanat Sharif University of Tehran - manager DevDiwan - CloudMTS ";
  }
}

$data = new AyhanGaraBay();
echo json_encode($data);
?>.

```

## Result: 
```
{
    "name": "Ayhan GaraBay",
    "age": 20,
    "education": "software engineering",
    "skills": [
        "Web",
        "Network and security",
        "application",
        "Ai"
    ],
    "interests": [
        "Cat developer",
        "Security specialist"
    ],
    "account": [
        "t.me/Ayhan_dev",
        "ayhan.gy.dev@gmail.com"
    ],
    "future_goals": "My ayhan GaraBay, fullstack developer / Sanat Sharif University of Tehran - manager DevDiwan - CloudMTS "
}
```


## Socials : 

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://Instagram.com/ayhan_G.y)[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/ayhan-gara-by-082080271) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/21669938)[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/Ayhan_Developer)[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](http://youtube.com/@AyhanG.Y) 

 
 
 ![♪ waving](https://capsule-render.vercel.app/api?type=waving&height=90&section=footer)

 
