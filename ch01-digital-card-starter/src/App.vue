<template>
  <div class="container mx-auto flex flex-col gap-5">

    <div class="flex items-center gap-4">
      <svg width="48" height="48" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M2 9V6.5C2 4.01 4.01 2 6.5 2H9" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M15 2H17.5C19.99 2 22 4.01 22 6.5V9" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M22 16V17.5C22 19.99 19.99 22 17.5 22H16" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M9 22H6.5C4.01 22 2 19.99 2 17.5V15" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M8.5 11C9.88071 11 11 9.88071 11 8.5C11 7.11929 9.88071 6 8.5 6C7.11929 6 6 7.11929 6 8.5C6 9.88071 7.11929 11 8.5 11Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M7.5 18C8.32843 18 9 17.3284 9 16.5C9 15.6716 8.32843 15 7.5 15C6.67157 15 6 15.6716 6 16.5C6 17.3284 6.67157 18 7.5 18Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M16.5 9C17.3284 9 18 8.32843 18 7.5C18 6.67157 17.3284 6 16.5 6C15.6716 6 15 6.67157 15 7.5C15 8.32843 15.6716 9 16.5 9Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M15.5 18C16.8807 18 18 16.8807 18 15.5C18 14.1193 16.8807 13 15.5 13C14.1193 13 13 14.1193 13 15.5C13 16.8807 14.1193 18 15.5 18Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
      <div class="flex flex-col gap-1">
        <strong class="text-2xl">کارت دیجیتال</strong>
        <span class="text-sm opacity-70">اطلاعات خود را وارد کنید تا کارت شما بلافاصله بروزرسانی شود.</span>
      </div>
    </div>

    <div class="w-full grid grid-cols-2 gap-5">
      <form class="w-full rounded-3xl bg-white border flex flex-col gap-5 p-5">
        <div class="flex flex-col gap-4">
          <div class="flex items-center gap-2">
            <span class="size-10 rounded-xl bg-gray-50 border grid place-items-center">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 2C9.38 2 7.25 4.13 7.25 6.75C7.25 9.32 9.26 11.4 11.88 11.49C11.96 11.48 12.04 11.48 12.1 11.49C12.12 11.49 12.13 11.49 12.15 11.49C12.16 11.49 12.16 11.49 12.17 11.49C14.73 11.4 16.74 9.32 16.75 6.75C16.75 4.13 14.62 2 12 2Z" fill="currentColor"/>
                <path d="M17.08 14.15C14.29 12.29 9.73996 12.29 6.92996 14.15C5.65996 15 4.95996 16.15 4.95996 17.38C4.95996 18.61 5.65996 19.75 6.91996 20.59C8.31996 21.53 10.16 22 12 22C13.84 22 15.68 21.53 17.08 20.59C18.34 19.74 19.04 18.6 19.04 17.36C19.03 16.13 18.34 14.99 17.08 14.15Z" fill="currentColor"/>
              </svg>
            </span>
            <strong class="text-xl">اطلاعات شخصی</strong>
          </div>
          <div class="w-full grid grid-cols-2 gap-4">

            <!-- نام و نام خانوادگی -->
            <div class="w-full flex flex-col gap-1">
              <label>نام و نام خانوادگی</label>
              <input type="text" placeholder="محمد رضایی">
            </div>

            <!-- سمت / عنوان شغلی -->
            <div class="w-full flex flex-col gap-1">
              <label>سمت / عنوان شغلی</label>
              <input type="text" placeholder="Full-Stack Developer">
            </div>

            <!-- شماره تلفن -->
            <div class="w-full flex flex-col gap-1">
              <label>شماره تلفن</label>
              <input type="text" placeholder="09123456789">
            </div>

            <!-- ایمیل -->
            <div class="w-full flex flex-col gap-1">
              <label>ایمیل</label>
              <input type="text" placeholder="example@domain.com">
            </div>

            <!-- تصویر -->
            <div class="w-full flex flex-col gap-1">
              <label>تصویر پروفایل</label>
              <div class="flex items-center gap-2">
                
                <!-- Image Preview -->
                <div class="bg-gray-100 p-2 rounded-lg border size-20 grid place-items-center">
                  <svg opacity="0.7" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M9 22H15C20 22 22 20 22 15V9C22 4 20 2 15 2H9C4 2 2 4 2 9V15C2 20 4 22 9 22Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M9 10C10.1046 10 11 9.10457 11 8C11 6.89543 10.1046 6 9 6C7.89543 6 7 6.89543 7 8C7 9.10457 7.89543 10 9 10Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M2.66992 18.95L7.59992 15.64C8.38992 15.11 9.52992 15.17 10.2399 15.78L10.5699 16.07C11.3499 16.74 12.6099 16.74 13.3899 16.07L17.5499 12.5C18.3299 11.83 19.5899 11.83 20.3699 12.5L21.9999 13.9" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                  </svg>
                </div>

                <label class="relative flex items-center gap-2 px-4 py-1 rounded-lg bg-gray-100 border cursor-pointer">
                  <input type="file" name="image" id="image" class="appearance-none opacity-0 absolute inset-0">
                  <svg opacity="0.6" width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M9.32007 6.5L11.8801 3.94L14.4401 6.5" stroke="currentColor" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M11.8799 14.18V4.00999" stroke="currentColor" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M4 12C4 16.42 7 20 12 20C17 20 20 16.42 20 12" stroke="currentColor" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                  </svg>
                  <span class="opacity-60">انتخاب تصویر</span>
                </label>

              </div>
            </div>

            <!-- درباره من -->
            <div class="w-full col-span-full flex flex-col gap-1">
              <label>درباره من</label>
              <textarea rows="4" class="w-full bg-transparent border rounded-lg p-2" placeholder="توضیحاتی در مورد خودتان اضافه کنید ..."></textarea>
            </div>

          </div>
        </div>
        <hr class="w-full opacity-10">
        <div class="flex flex-col gap-4">
          <div class="flex items-center gap-2">
            <span class="size-10 rounded-xl bg-gray-50 border grid place-items-center">
              <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M13.0601 10.94C15.3101 13.19 15.3101 16.83 13.0601 19.07C10.8101 21.31 7.17009 21.32 4.93009 19.07C2.69009 16.82 2.68009 13.18 4.93009 10.94" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                <path d="M10.59 13.41C8.24996 11.07 8.24996 7.27 10.59 4.92C12.93 2.57 16.73 2.58 19.08 4.92C21.43 7.26 21.42 11.06 19.08 13.41" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </span>
            <strong class="text-xl">شبکه های اجتماعی</strong>
          </div>

          <div class="w-full grid grid-cols-2 gap-4" dir="ltr">
            
            <!-- Github -->
            <div class="w-full p-4 rounded-lg border flex items-center gap-4">
              <img src="./assets/icons/github.svg" alt="github" class="w-8">
              <div class="flex flex-col gap-1">
                <label>Github</label>
                <input type="text" class="w-full bg-transparent appearance-none" placeholder="https://github.com/username">
              </div>
            </div>

            <!-- LinkedIn -->
            <div class="w-full p-4 rounded-lg border flex items-center gap-4">
              <img src="./assets/icons/linkedin.svg" alt="linkedin" class="w-8">
              <div class="flex flex-col gap-1">
                <label>Linkedin</label>
                <input type="text" class="w-full bg-transparent appearance-none" placeholder="https://linkedin.com/username">
              </div>
            </div>

            <!-- Telegram -->
            <div class="w-full p-4 rounded-lg border flex items-center gap-4">
              <img src="./assets/icons/telegram.svg" alt="telegram" class="w-8">
              <div class="flex flex-col gap-1">
                <label>Telegram</label>
                <input type="text" class="w-full bg-transparent appearance-none" placeholder="https://t.me/username">
              </div>
            </div>

            <!-- Instagram -->
            <div class="w-full p-4 rounded-lg border flex items-center gap-4">
              <img src="./assets/icons/instagram.svg" alt="instagram" class="w-8">
              <div class="flex flex-col gap-1">
                <label>Instagram</label>
                <input type="text" class="w-full bg-transparent appearance-none" placeholder="https://instagram.com/username">
              </div>
            </div>

          </div>

        </div>
      </form>

      <div class="w-full h-full bg-[url('../assets/bg.png')] bg-cover bg-center rounded-3xl grid place-items-center p-10 relative">

        <!-- Title -->
        <div class="flex items-center absolute right-5 top-5 gap-2 text-white select-none">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M15.58 12C15.58 13.98 13.98 15.58 12 15.58C10.02 15.58 8.42004 13.98 8.42004 12C8.42004 10.02 10.02 8.42004 12 8.42004C13.98 8.42004 15.58 10.02 15.58 12Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
            <path d="M12 20.27C15.53 20.27 18.82 18.19 21.11 14.59C22.01 13.18 22.01 10.81 21.11 9.39997C18.82 5.79997 15.53 3.71997 12 3.71997C8.46997 3.71997 5.17997 5.79997 2.88997 9.39997C1.98997 10.81 1.98997 13.18 2.88997 14.59C5.17997 18.19 8.46997 20.27 12 20.27Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
          </svg>
          پیش نمایش کارت دیجیتال
        </div>

        <div class="w-full p-10 rounded-2xl bg-cover bg-center bg-[url('../assets/card-bg.png')] flex flex-col gap-10 text-white shadow-xl border-2 border-white/30">

          <!-- اطلاعات شخصی -->
          <div class="flex gap-5">
            <!-- تصویر پروفایل -->
            <div class="w-1/5 aspect-square h-full rounded-full border-5 border-white bg-slate-600 grid place-items-center">
              <svg opacity="0.7" width="48" height="48" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M9 22H15C20 22 22 20 22 15V9C22 4 20 2 15 2H9C4 2 2 4 2 9V15C2 20 4 22 9 22Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                <path d="M9 10C10.1046 10 11 9.10457 11 8C11 6.89543 10.1046 6 9 6C7.89543 6 7 6.89543 7 8C7 9.10457 7.89543 10 9 10Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
                <path d="M2.66992 18.95L7.59992 15.64C8.38992 15.11 9.52992 15.17 10.2399 15.78L10.5699 16.07C11.3499 16.74 12.6099 16.74 13.3899 16.07L17.5499 12.5C18.3299 11.83 19.5899 11.83 20.3699 12.5L21.9999 13.9" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
            </div>

            <!-- اطلاعات -->
            <div class="flex-1 flex flex-col gap-2">
              <strong class="text-3xl">سجاد میرشبی</strong>
              <span class="opacity-60">Full-Stack Developer</span>
              <div class="w-20 h-1 rounded-full bg-indigo-500"></div>
              <p class="opacity-70 text-justify text-sm">
                لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده از طراحان گرافیک است چاپگرها و متون بلکه روزنامه و مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای کاربردی می باشد کتابهای زیادی در شصت و سه درصد گذشته حال و آینده
              </p>
            </div>
          </div>

          <div class="w-full flex items-center justify-between">

            <!-- شبکه های اجتماعی -->
            <ul class="flex gap-4 items-center">
              <li><a href=""><img src="./assets/icons/github.svg" alt="github" class="invert w-8"></a></li>
              <li><a href=""><img src="./assets/icons/linkedin.svg" alt="linkedin" class=" w-8"></a></li>
              <li><a href=""><img src="./assets/icons/telegram.svg" alt="telegram" class=" w-8"></a></li>
              <li><a href=""><img src="./assets/icons/instagram.svg" alt="instagram" class="invert w-8"></a></li>
            </ul>

            <!-- شماره تماس و ایمیل -->
             <div class="flex flex-col gap-4" dir="ltr">
              <div class="flex items-center gap-2">
                <svg opacity="0.7" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M21.97 18.33C21.97 18.69 21.89 19.06 21.72 19.42C21.55 19.78 21.33 20.12 21.04 20.44C20.55 20.98 20.01 21.37 19.4 21.62C18.8 21.87 18.15 22 17.45 22C16.43 22 15.34 21.76 14.19 21.27C13.04 20.78 11.89 20.12 10.75 19.29C9.6 18.45 8.51 17.52 7.47 16.49C6.44 15.45 5.51 14.36 4.68 13.22C3.86 12.08 3.2 10.94 2.72 9.81C2.24 8.67 2 7.58 2 6.54C2 5.86 2.12 5.21 2.36 4.61C2.6 4 2.98 3.44 3.51 2.94C4.15 2.31 4.85 2 5.59 2C5.87 2 6.15 2.06 6.4 2.18C6.66 2.3 6.89 2.48 7.07 2.74L9.39 6.01C9.57 6.26 9.7 6.49 9.79 6.71C9.88 6.92 9.93 7.13 9.93 7.32C9.93 7.56 9.86 7.8 9.72 8.03C9.59 8.26 9.4 8.5 9.16 8.74L8.4 9.53C8.29 9.64 8.24 9.77 8.24 9.93C8.24 10.01 8.25 10.08 8.27 10.16C8.3 10.24 8.33 10.3 8.35 10.36C8.53 10.69 8.84 11.12 9.28 11.64C9.73 12.16 10.21 12.69 10.73 13.22C11.27 13.75 11.79 14.24 12.32 14.69C12.84 15.13 13.27 15.43 13.61 15.61C13.66 15.63 13.72 15.66 13.79 15.69C13.87 15.72 13.95 15.73 14.04 15.73C14.21 15.73 14.34 15.67 14.45 15.56L15.21 14.81C15.46 14.56 15.7 14.37 15.93 14.25C16.16 14.11 16.39 14.04 16.64 14.04C16.83 14.04 17.03 14.08 17.25 14.17C17.47 14.26 17.7 14.39 17.95 14.56L21.26 16.91C21.52 17.09 21.7 17.3 21.81 17.55C21.91 17.8 21.97 18.05 21.97 18.33Z" stroke="currentColor" stroke-width="1.5" stroke-miterlimit="10"/>
                </svg>
                <span>09123456789</span>
              </div>
              <div class="flex items-center gap-2">
                <svg opacity="0.7" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M2 8.5C2 5 4 3.5 7 3.5H17C20 3.5 22 5 22 8.5V15.5C22 19 20 20.5 17 20.5H7" stroke="currentColor" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M17 9L13.87 11.5C12.84 12.32 11.15 12.32 10.12 11.5L7 9" stroke="currentColor" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M2 16.5H8" stroke="currentColor" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M2 12.5H5" stroke="currentColor" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <span>example@domain.com</span>
              </div>
             </div>

          </div>

        </div>

      </div>

    </div>

  </div>
</template>

<script lang="ts" setup>

</script>

<style>

</style>