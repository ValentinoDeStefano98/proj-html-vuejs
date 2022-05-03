<template>
  <div class="py-5">
    <div class="text-center">
      <h2>Recent Courses</h2>
      <div class="d-flex justify-content-center">
        <nav class="navbar navbar-expand-lg navbar-light text-center">
          <div class="container-fluid text-center">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0" v-for="(elem, index) in arrayCategories" :key="index">
                <li class="nav-item">
                  <a v-bind:class="{ 'text-secondary' : elem.active }" class="nav-link text-primary" aria-current="page" href="#">{{ elem.name }}</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </div>
      <div class="container">
        <div class="row py-4">
          <div class="col-2" v-for="(elem, index) in arrayCard" :key="index">
            <div class="card">
              <img src="./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg" class="card-img-top" alt="...">
              <div class="card-body">
                <div class="text-start">
                  <span class="text-secondary size">{{elem.category}}</span>               
                <h6 class="card-title pt-2">{{elem.name}}</h6>
                </div>
                <hr>
                <div class="container p-0 m-0">
                  <div class="row">
                    <div class="col-8 text-start size">
                      <span class="my-3" v-if="elem.rating !== ''">
                            <i class="fa-solid fa-star" :class="elem.rating >= 1 ? 'text-warning' : ''"></i>
                            <i class="fa-solid fa-star" :class="elem.rating >= 2 ? 'text-warning' : ''"></i>
                            <i class="fa-solid fa-star" :class="elem.rating >= 3 ? 'text-warning' : ''"></i>
                            <i class="fa-solid fa-star" :class="elem.rating >= 4 ? 'text-warning' : ''"></i>
                            <i class="fa-solid fa-star" :class="elem.rating == 5 ? 'text-warning' : ''"></i>
                            {{elem.rating}} 
                      </span>
                      <span v-if="elem.time != ''" class="size"><i class="fa-regular fa-clock"></i> {{ elem.time }}</span>
                    </div>
                    <div class="col-4 text-end size">                    
                      <span v-bind:class="{discounted : elem.discounted == true}" class="fw-bold">{{elem.originalPrice}}</span>
                      <div v-if="elem.discount !== ''">{{ elem.discount }}</div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>        
        </div>
      </div>
    </div>   
  </div>
</template>

<script>
export default {
  name: 'RecentCoursesComp',
  data() {
    return {
      arrayCategories: [{
            "name": "All Categories",
            "link": "#",
            "active": true
        },
        {
            "name": "Art",
            "link": "#",
        },
        {
            "name": "Exercise",
            "link": "#",
        },
        {
            "name": "Material Design",
            "link": "#",
        },
        {
            "name": "Music",
            "link": "#",
        },
        {
            "name": "Photography",
            "link": "#",
        },
        {
            "name": "Software Development",
            "link": "#",
        },
        ],
        arrayCard: [{
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Apache >",
            "name": "Web Coding and Apache Basics",
            "time": "6 hours",
            "rating": "",
            "originalPrice": "Free",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Art >",
            "name": "Real Things Art Painting by Jason Ni",
            "time": "6 hours",
            "rating": "",
            "originalPrice": "$60",
            "discount": "$45",
            "discounted": true,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Software Development >",
            "name": "Basics of MasterStudy",
            "time": "",
            "rating": "5",
            "originalPrice": "Free",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Electronic >",
            "name": "How to be a DJ? Make Electronic Music",
            "time": "",
            "rating": "5",
            "originalPrice": "$59",
            "discount": "$49",
            "discounted": true,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Communication >",
            "name": "Design Instrument for Communication",
            "time": "6 hours",
            "rating": "",
            "originalPrice": "",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Art >",
            "name": "Make your Concept Right and Beautiful",
            "time": "6 hours",
            "rating": "",
            "originalPrice": "$70",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Bicycling >",
            "name": "Road Bike Manual or How to Be a Champion.",
            "time": "6 hours",
            "rating": "",
            "originalPrice": "$20",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Documentary >",
            "name": "How to Make Beautiful Landscape photos?",
            "time": "6 hours",
            "rating": "",
            "originalPrice": "$60",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Art >",
            "name": "Let's paint Van Gogh's Starry Night",
            "time": "6 hours",
            "rating": "",
            "originalPrice": "$79",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Nvidia >",
            "name": "Nvidia and UE4 Technologies Practice",
            "time": "",
            "rating": "5",
            "originalPrice": "Free",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Art >",
            "name": "How to Work with Legendary RED camera?",
            "time": "6 hours",
            "rating": "",
            "originalPrice": "Free",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        {
            "poster": "./../../assets/img/photo-1461749280684-dccba630e2f6-544x322.jpeg",
            "category": "Software Development >",
            "name": "MasterStudy Mobile LMS App",
            "time": "2 hours",
            "rating": "",
            "originalPrice": "Free",
            "discount": "",
            "discounted": false,
            "link": "#",
        },
        ],
    }
    }
}
</script>

<style scoped lang="scss">
.container{
  width: 90%;
  margin: 0 auto;
}

.btn{
  border-radius: 30px;
}

.size{
  font-size: 0.8em;
}

.active{
  color: grey;
}

.discounted{
  color: grey;
  text-decoration: line-through;
}
</style>