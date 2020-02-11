# ngSwipper

html
----------------- 
<div class="swiper-container" [swiper]="config">
            <div class="swiper-wrapper">
              <div class="swiper-slide"><i class="fa fa-arrows" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-expand" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-text-height" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-list-ul" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-cog" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-glass" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-sort-alpha-desc" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-bold" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-link" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-arrow-left" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-arrows" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-expand" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-text-height" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-list-ul" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-cog" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-glass" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-sort-alpha-desc" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-bold" aria-hidden="true"></i></div>
              <div class="swiper-slide"><i class="fa fa-link" aria-hidden="true"></i></div>
            </div>
            <!-- Add Arrows -->
            <div class="swiper-button-next"></div>
            <div class="swiper-button-prev"></div>
          </div>


.ts
------------------
 import { SwiperConfigInterface } from 'ngx-swiper-wrapper';

// config: SwiperConfigInterface = {
  //   direction: 'vertical',
  //   autoHeight: true,
  //   slidesPerView: 9,
  //   navigation: {
  //     nextEl: '.swiper-button-next',
  //     prevEl: '.swiper-button-prev',
  //   },
  //   breakpoints: {
  //     320: {
  //       slidesPerView: 4,
  //     },
  //     640: {
  //       slidesPerView: 4,
  //     },
  //     768: {
  //       slidesPerView: 6,
  //     },
  //     1200: {
  //       slidesPerView: 9,
  //     },
  //   }
  // }; 


package.json 
------------
"ngx-swiper-wrapper": "^8.0.2"

app.module.ts
--------------
import { SwiperModule } from 'ngx-swiper-wrapper';

@NgModule({
  imports: [SwiperModule]
})
