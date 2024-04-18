
for this tailwind design take all inline class and make custom class using @apply 
like this 
`.custom-section { 
@apply my-8 divide-y-2 divide-gray-100
}
`
 take all classes from html and convert then to custom classs
```
<div class="my-8 divide-y-2 divide-gray-100 ">
      
      <div class="py-3 flex flex-wrap md:flex-nowrap">

        <div class="md:w-36 2xl:w-64 md:mb-0 mb-3 flex-shrink-0 flex flex-col">
          <span >CATEGORY</span>
        </div>

        <div class="md:flex-grow">

          <p>Glossier echo park pug, church-key sartorial biodiesel vexillologist pop-up snackwave ramps cornhole. Marfa 3 wolf moon party messenger bag selfies, poke vaporware kombucha lumbersexual pork belly polaroid hoodie portland craft beer.</p>

        </div>
      </div>

      <div class="py-3 flex flex-wrap md:flex-nowrap">

        <div class="md:w-36 2xl:w-64 md:mb-0 mb-3 flex-shrink-0 flex flex-col">
          <span >CATEGORY</span>
        </div>

        <div class="md:flex-grow">

          <p>Glossier echo park pug, church-key sartorial biodiesel vexillologist pop-up snackwave ramps cornhole. Marfa 3 wolf moon party messenger bag selfies, poke vaporware kombucha lumbersexual pork belly polaroid hoodie portland craft beer.</p>

        </div>
      </div>


    </div>
