<template>
  <div class="shadow-xl m-10">
    <table class="text-sm w-full rounded-xl">
      <thead>
        <tr class="shadow border text-sm bg-gray-100">
          <th class="border-b font-medium pt-3 pb-3 text-left pl-5">Name</th>
          <th class="border-b font-medium pt-3 pb-3 text-left">Title</th>
          <th class="border-b font-medium pt-3 pb-3 text-left">Email</th>
          <th class="border-b font-medium pt-3 pb-3 text-left">Role</th>
          <th class="border-b"></th>
        </tr>
      </thead>
      <tbody>
        <tr class="border-b">
          <td class="font-sans pl-5 py-5">
            <div class="flex items-center space-x-2">
              <img class="flex-none w-8 h-8 rounded-full object-cover" src="public\foto.jpeg">
              <span>Lindisay Wilson</span>
            </div>
          </td>
          <td class="text-slate-500 font-sans py-5 ">Front-End Developer</td>
          <td class="text-slate-500 py-5">lindsay.walton@example.com</td>
          <td class="text-slate-500 py-5">
            <div class="flex">
              <span class="flex bg-green-100 rounded-full text-green-800 text-xs px-2 py-1 leading-none ">Admin</span>
            </div>
          </td>
          <td class="border-r border-gray-200 text-slate-500 py-5">
            
            <div class="flex text-right">
              <a href="#" class="">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 hover:text-black">
                  <path d="M5.433 13.917l1.262-3.155A4 4 0 017.58 9.42l6.92-6.918a2.121 2.121 0 013 3l-6.92 6.918c-.383.383-.84.685-1.343.886l-3.154 1.262a.5.5 0 01-.65-.65z" />
                  <path d="M3.5 5.75c0-.69.56-1.25 1.25-1.25H10A.75.75 0 0010 3H4.75A2.75 2.75 0 002 5.75v9.5A2.75 2.75 0 004.75 18h9.5A2.75 2.75 0 0017 15.25V10a.75.75 0 00-1.5 0v5.25c0 .69-.56 1.25-1.25 1.25h-9.5c-.69 0-1.25-.56-1.25-1.25v-9.5z" />
                </svg>
              </a>
              <a href="#" class="ml-4">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 hover:text-red-600">
                  <path d="M2 3a1 1 0 00-1 1v1a1 1 0 001 1h16a1 1 0 001-1V4a1 1 0 00-1-1H2z" />
                  <path fill-rule="evenodd" d="M2 7.5h16l-.811 7.71a2 2 0 01-1.99 1.79H4.802a2 2 0 01-1.99-1.79L2 7.5zm5.22 1.72a.75.75 0 011.06 0L10 10.94l1.72-1.72a.75.75 0 111.06 1.06L11.06 12l1.72 1.72a.75.75 0 11-1.06 1.06L10 13.06l-1.72 1.72a.75.75 0 01-1.06-1.06L8.94 12l-1.72-1.72a.75.75 0 010-1.06z" clip-rule="evenodd" />
                </svg>
              </a>
            </div>
          </td>
        </tr>
        <tr class="border-b">
          <td class="font-sans pl-5 py-5">
            <div class="flex items-center space-x-2">
              <img class="flex-none w-8 h-8 rounded-full object-cover" src="public\foto.jpeg">
              <span>Lindisay Wilson</span>
            </div>
          </td>
          <td class="text-slate-500 font-sans py-5 ">Front-End Developer</td>
          <td class="text-slate-500 py-5">lindsay.walton@example.com</td>
          <td class="text-slate-500 py-5">
            <div class="flex">
              <span class="flex bg-green-100 rounded-full text-green-800 text-xs px-2 py-1 leading-none ">Admin</span>
            </div>
          </td>
          <td class="border-r border-gray-200 text-slate-500 py-5">
            
            <div class="flex text-right">
              <a href="#" class="">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 hover:text-black">
                  <path d="M5.433 13.917l1.262-3.155A4 4 0 017.58 9.42l6.92-6.918a2.121 2.121 0 013 3l-6.92 6.918c-.383.383-.84.685-1.343.886l-3.154 1.262a.5.5 0 01-.65-.65z" />
                  <path d="M3.5 5.75c0-.69.56-1.25 1.25-1.25H10A.75.75 0 0010 3H4.75A2.75 2.75 0 002 5.75v9.5A2.75 2.75 0 004.75 18h9.5A2.75 2.75 0 0017 15.25V10a.75.75 0 00-1.5 0v5.25c0 .69-.56 1.25-1.25 1.25h-9.5c-.69 0-1.25-.56-1.25-1.25v-9.5z" />
                </svg>
              </a>
              <a href="#" class="ml-4">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 hover:text-red-600">
                  <path d="M2 3a1 1 0 00-1 1v1a1 1 0 001 1h16a1 1 0 001-1V4a1 1 0 00-1-1H2z" />
                  <path fill-rule="evenodd" d="M2 7.5h16l-.811 7.71a2 2 0 01-1.99 1.79H4.802a2 2 0 01-1.99-1.79L2 7.5zm5.22 1.72a.75.75 0 011.06 0L10 10.94l1.72-1.72a.75.75 0 111.06 1.06L11.06 12l1.72 1.72a.75.75 0 11-1.06 1.06L10 13.06l-1.72 1.72a.75.75 0 01-1.06-1.06L8.94 12l-1.72-1.72a.75.75 0 010-1.06z" clip-rule="evenodd" />
                </svg>
              </a>
            </div>
          </td>
        </tr>
        <tr class="border-b">
          <td class="font-sans pl-5 py-5">
            <div class="flex items-center space-x-2">
              <img class="flex-none w-8 h-8 rounded-full object-cover" src="public\foto.jpeg">
              <span>Lindisay Wilson</span>
            </div>
          </td>
          <td class="text-slate-500 font-sans py-5 ">Front-End Developer</td>
          <td class="text-slate-500 py-5">lindsay.walton@example.com</td>
          <td class="text-slate-500 py-5">
            <div class="flex">
              <span class="flex bg-green-100 rounded-full text-green-800 text-xs px-2 py-1 leading-none ">Admin</span>
            </div>
          </td>
          <td class="border-r border-gray-200 text-slate-500 py-5">
            
            <div class="flex text-right">
              <a href="#" class="">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 hover:text-black">
                  <path d="M5.433 13.917l1.262-3.155A4 4 0 017.58 9.42l6.92-6.918a2.121 2.121 0 013 3l-6.92 6.918c-.383.383-.84.685-1.343.886l-3.154 1.262a.5.5 0 01-.65-.65z" />
                  <path d="M3.5 5.75c0-.69.56-1.25 1.25-1.25H10A.75.75 0 0010 3H4.75A2.75 2.75 0 002 5.75v9.5A2.75 2.75 0 004.75 18h9.5A2.75 2.75 0 0017 15.25V10a.75.75 0 00-1.5 0v5.25c0 .69-.56 1.25-1.25 1.25h-9.5c-.69 0-1.25-.56-1.25-1.25v-9.5z" />
                </svg>
              </a>
              <a href="#" class="ml-4">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 hover:text-red-600">
                  <path d="M2 3a1 1 0 00-1 1v1a1 1 0 001 1h16a1 1 0 001-1V4a1 1 0 00-1-1H2z" />
                  <path fill-rule="evenodd" d="M2 7.5h16l-.811 7.71a2 2 0 01-1.99 1.79H4.802a2 2 0 01-1.99-1.79L2 7.5zm5.22 1.72a.75.75 0 011.06 0L10 10.94l1.72-1.72a.75.75 0 111.06 1.06L11.06 12l1.72 1.72a.75.75 0 11-1.06 1.06L10 13.06l-1.72 1.72a.75.75 0 01-1.06-1.06L8.94 12l-1.72-1.72a.75.75 0 010-1.06z" clip-rule="evenodd" />
                </svg>
              </a>
            </div>
          </td>
        </tr>
        <tr class="border-b">
          <td class="font-sans pl-5 py-5">
            <div class="flex items-center space-x-2">
              <img class="flex-none w-8 h-8 rounded-full object-cover" src="public\foto.jpeg">
              <span>Lindisay Wilson</span>
            </div>
          </td>
          <td class="text-slate-500 font-sans py-5 ">Front-End Developer</td>
          <td class="text-slate-500 py-5">lindsay.walton@example.com</td>
          <td class="text-slate-500 py-5">
            <div class="flex">
              <span class="flex bg-green-100 rounded-full text-green-800 text-xs px-2 py-1 leading-none ">Admin</span>
            </div>
          </td>
          <td class="border-r border-gray-200 text-slate-500 py-5">
            
            <div class="flex text-right">
              <a href="#" class="">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 hover:text-black">
                  <path d="M5.433 13.917l1.262-3.155A4 4 0 017.58 9.42l6.92-6.918a2.121 2.121 0 013 3l-6.92 6.918c-.383.383-.84.685-1.343.886l-3.154 1.262a.5.5 0 01-.65-.65z" />
                  <path d="M3.5 5.75c0-.69.56-1.25 1.25-1.25H10A.75.75 0 0010 3H4.75A2.75 2.75 0 002 5.75v9.5A2.75 2.75 0 004.75 18h9.5A2.75 2.75 0 0017 15.25V10a.75.75 0 00-1.5 0v5.25c0 .69-.56 1.25-1.25 1.25h-9.5c-.69 0-1.25-.56-1.25-1.25v-9.5z" />
                </svg>
              </a>
              <a href="#" class="ml-4">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-5 h-5 hover:text-red-600">
                  <path d="M2 3a1 1 0 00-1 1v1a1 1 0 001 1h16a1 1 0 001-1V4a1 1 0 00-1-1H2z" />
                  <path fill-rule="evenodd" d="M2 7.5h16l-.811 7.71a2 2 0 01-1.99 1.79H4.802a2 2 0 01-1.99-1.79L2 7.5zm5.22 1.72a.75.75 0 011.06 0L10 10.94l1.72-1.72a.75.75 0 111.06 1.06L11.06 12l1.72 1.72a.75.75 0 11-1.06 1.06L10 13.06l-1.72 1.72a.75.75 0 01-1.06-1.06L8.94 12l-1.72-1.72a.75.75 0 010-1.06z" clip-rule="evenodd" />
                </svg>
              </a>
            </div>
          </td>
        </tr>
      </tbody>
    
      <!--
      <tr>
        <th>
          Name
        </th>
        <th>
          Title
        </th>
        <th>
          Email
        </th>
        <th>
          Role
        </th>
        <th></th>
      </tr>
      <tr>
        <td>
          Lindsay Walton
        </td>
        <td>
          Front-End Developer
        </td>
        <td>
          lindsay.walton@example.com
        </td>
        <td>
          Member
        </td>
        <td><a href="#">Edit</a></td>
      </tr>
      -->
    </table>
  </div>

<hr>
</template>