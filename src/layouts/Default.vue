<template>
  <div class="font-sans text-grey-800 leading-normal flex flex-col min-h-screen">
    <header>
      <nav class="container mx-auto flex justify-between items-center py-8">
        <p></p>
        <ul class="uppercase tracking-wide flex items-center">
          <li class="mr-8"><a href="#" class="text-gray-600 hover:text-green-600">Work</a></li>
          <li class="mr-8"><a href="#" class="text-gray-600 hover:text-green-600">Contact</a></li>
        </ul>
      </nav>
    </header> 
    <div class="flex-grow">
      <slot/>
    </div>
    <footer>
      <div class="container mx-auto flex items-center justify-between py-8">
        <ul class="flex items-center mb-8">
          <li class="mr-8">
            <a href="https://github.com/adamkea" class="text-gray-600 hover:text-green-600">Github</a>
          </li>
          <li class="mr-8">
            <a href="https://www.linkedin.com/in/admkearney/" class="text-gray-600 hover:text-green-600">LinkedIn</a>
          </li>
          <li class="mr-8">
            <a href="mailto:adamkearney@live.com" class="text-gray-600 hover:text-green-600">Email</a>
          </li>
        </ul>
      </div>  
    </footer>
  </div>
</template>

<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>

<style src="../main.css"/>
