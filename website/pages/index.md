---
layout: "ssg-theme-astro/layouts/main.astro"  # This line of code should remain unchanged.
tag: "GTM-5X48JDV2"
title: "Dim Sum Club 點心薈 - Best Food Today"
favicon: "favicon.ico" #ico is best
logo: "點心薈LOGO-定.webp"
primaryColor: "#7E1C1D" # logo color
secondaryColor: "#EBB73D"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "light"
cuid: ""
ruid: ""
orderOnlineLink: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b"
# tableReservationLink: "https://www.bestfoodtodayus.com/ordering/restaurant/menu/reservation?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b&reservation=true&client_is_mobile=true"
tel: "415-579-3688"

# banner:
#   text: 
#     # - boldText: "🥳 Special Offer"
#     - boldText: "20% off cash discount"
#     - text: " on xxx"
#     - smText: ""
#   # add more text...
#   textColor: "#ffffff"
#   bgColor: "#E7383D"
#   bgOpacity: "1" # 0~1

# header
header:
  logoSize: 50
  textAfterLogo: 
    text: ""
    size: 20
    color: ""
  logoOnMobile: "點心薈LOGO-mobile.webp"
  bgColor: "#fff"
  bgOpacity: "0.9" # 0~1
  menuTextColor: "#000"
  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "#about-us" }
    - { text: "Contact Us", link: "#contact-us" }
    - { text: "中文", link: "/zh-cn" }
  
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  telTextColor: "#000000"
  addTelBtn: true
  otherBtn1InsteadText: "Order Oline"
  otherBtn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b"
  otherBtn2InsteadText: "Reservation"
  otherBtn2Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu/reservation?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b&reservation=true&client_is_mobile=true"

sections:
# hero
  - type: "hero" 
    id: ""
    height: "80" # Conditionally use only when sectionType is imgBg
    sectionType: "video" # video | imgWithText | imgBg
    bgVideoType: "gjw" # youtube | vimeo | gjw
    bgVideoId: "1gus30l309e3Pb9AhQptQPgTK1pv1c"
    bgImg: "Dim Sum Club 點心薈.webp"
    bgColor: "#000000"
    bgOpacity: "0.5" # 0~1
    title: 
      - "Dim Sum Club"
      - "點心薈"
    titleColor: "#ffffff"
    description: 
      - "Welcome to Dim Sum Club, Come and enjoy your day with traditional handmade Cantonese style dim sums!"
    descriptionColor: "#ffffff"
    isTextAlignCenter: true
    # title2: 
    #   - ""
    # title2Color: "#ffffff"
    # description2: 
    #   - ""
    # description2Color: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""

    btn1Text: "See MENU & Order"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b" 
    btn2Text: "Tel: (415) 579-3688" 
    btn2Href: "tel: 415-579-3688" 

    bannerImg: ""
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
   
    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"

# Video
  - type: "video"
    id: "video"
    title: 
      - "Dim Sum Club 點心薈"
    description: 
      - "Come and savor our delicious selections!" 
    videoType: "gjw" # vimeo | gjw | youtube
    videoId: 
      - "1gus30l309e3Pb9AhQptQPgTK1pv1c"
    isOnlyDisplayOnMobile: true

# Gallery - menu
  - type: "gallery"
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Delicious Dim Sum"
    titleColor: "#000000"
    description: 
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery1"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

# Gallery - menu
  - type: "gallery"
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Delicious Cuisine"
    titleColor: "#000000"
    description: 
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

# textBlock - about us
  - type: "textBlock" 
    id: "about-us"
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "About Dim Sum Club"
      - "點心薈"
    titleColor: "#000000"
    description: 
      - "Welcome to Dim Sum Club,  Come and enjoy your day with traditional handmade Cantonese style dim sums such as shrimp dumplings (Har Gow) , chives & shrimp dumplings, Pork dumpling (Siu Mai), BBQ Pork Bun, Techew dumpling, Shanghai dumpling & rice noodle rolls. We also serve traditional Chinese style seafood dishes. Dim Sum Club offers the authentic taste at reasonable price."
    descriptionColor: ""

# Gallery - Welcome To Dim Sum Club 點心薈
  - type: "gallery"
    id: ""
    mode: 3 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Welcome To Dim Sum Club"
      - "點心薈"
    titleColor: ""
    description: 
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery2"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full


# # feature - imgWithText
#   - type: "feature" 
#     noMarginTop: true
#     id: ""
#     height: "100" # Conditionally use only when sectionType is imgBg
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     title: 
#       - "Lorem ipsum dolor sit ame"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     descriptionColor: "#000000"

#     addOrderOnlineBtn: false
#     orderOnlineBtnInsteadText: ""
#     addTableReservationBtn: false
#     tableReservationBtnInsteadText: ""

#     btn1Text: "" 
#     btn1Href: "" 
#     btn2Text: "" 
#     btn2Href: "" 

#     bannerImg: "sample.webp"
#     imgPosition: "imgLeft" # imgLeft | imgRight
#     bannerMarginTopMobile: 20
#     imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

# # feature - map
#   - type: "feature" 
#     id: ""
#     noMarginTop: false
#     sectionType: "imgWithText" # video | imgWithText | imgBg
#     title: 
#       - "Store 2 : Washington St"
#     titleColor: "#000000"
#     description: 
#       - "Opening Hours: "
#       - "Mon-Fri 8:30 AM-8:00 PM, Sat-Sun 9:00 AM-8:30 PM"
#     descriptionColor: "#000000"

#     addOrderOnlineBtn: true
#     orderOnlineBtnInsteadText: ""
#     addTableReservationBtn: true
#     tableReservationBtnInsteadText: ""
#     showOtherBtn: true
#     btn1Text: "Order online from Washington St Store" 
#     btn1Href: "#" 
#     btn2Text: "" 
#     btn2Href: "" 

#     map: true
#     url: "https://maps.app.goo.gl/HDDb5yFih4S8TmDe7"
#     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d197.0491990412703!2d-122.4063506!3d37.7950269!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085815e4be59617%3A0x87622e118f7e38a2!2sHon%E2%80%99s%20Wun-Tun%20House!5e0!3m2!1sen!2sjp!4v1722232541079!5m2!1sen!2sjp"
#     addTelBtn: true
#     tel: "12345678"
#     telInsteadText: "Call: (123) 456-7890"
#     tel2: "876543210" # if there are two phone numbers"
#     tel2InsteadText: "Call: (876) 543-2100"
#     getDirectionBtnInsteadText: ""
#     imgPosition: "" # imgLeft | imgRight




# # textBlock 
#   - type: "textBlock" 
#     id: "about-us"
#     bgImg: ""
#     bgColor: ""
#     bgOpacity: "" # 0~1
#     title: 
#       - "About Us"
#     titleColor: "#000000"
#     description: 
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
#       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
#     descriptionColor: "#000000"

# textBlock - Information - NEW! Online Ordering
  - type: "textBlock" 
    noMarginTop: false
    id: ""
    bgImg: "Dim Sum Club 點心薈a.webp"
    bgColor: "#000"
    bgOpacity: "0.6" # 0~1
    title: 
      - "NEW! Online Ordering"
    titleColor: "#ffffff"
    description: 
      - "Online ordering NOW enabled for pick-up. Just tell us what you want and we'll prepare it as fast as we can. All orders are manually confirmed by us directly. Find out in real-time when your food is ready. All orders are manually confirmed by us in real-time. Watch on-screen when your food is ready for pickup."
    descriptionColor: "#ffffff"
  
# map  
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/8jTL3ZwV9JjpWQiQA"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d914.3236446052001!2d-122.49179671757695!3d37.742276930733766!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808f7d82ee0f4663%3A0xde21cc529fccf39d!2zRGltIFN1bSBDbHViIOm7nuW_g-iWiA!5e0!3m2!1sen!2sus!4v1723080951228!5m2!1sen!2sus"
    addTelBtn: true
    tel: ""
    telInsteadText: "Tel: 415-579-3688"
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: ""
 
#  # The modal will only appear once within 30 minutes."
#   - type: "modal" 
#     bgColor: "#333"
#     bgOpacity: "0.1" # 0~1
#     title: 
#       - "🎁 Special Offers"
#     titleColor: "#FF2D2F"
#     titleSize: 24
#     description: 
#       - "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     descriptionColor: ""
#     descriptionSize: 16
#     imgName: "special_offer.webp"
#     imgAlt: "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     imgHref: ""
#     buttonText: ""

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: "gallery2/001_Dim Sum Club interior.webp"
  bgColor: "#000"
  bgOpacity: "0.7" # 0~1
  textColor: "#fff" # default white

  openingHoursInsteadText: ""
  openingHours: 
    - "Mon, Wed-Fri"
    - "10:30 AM - 3:00 PM, 5:00 PM - 9:00 PM"
    - "Sat-Sun"
    - "10:00 AM - 3:00 PM, 5:00 PM - 9:00 PM"
    - "Tue: Closed"
  
  isLogo: false
  logoSize: 120
 
  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "/#about-us" }
    - { text: "Contact Us", link: "/#contact-us" }
    - { text: "中文", link: "/zh-cn" }

  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""
  doorDash: true
  doorDashLink: "https://www.doordash.com/store/dim-sum-club-san-francisco-1654701/"
  uberEats: true
  uberEatsLink: "https://www.ubereats.com/store/dim-sum-club/uaVtE5tHR3S6AipUh3-1ug"

  acceptedPaymentMethodsInsteadText: ""
  paymentMethod: "cash,visa,amex,alipay,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  # at a minimum, please make sure to include the meta description.
seo:
  metaTitle: "Dim Sum Club 點心薈 - Authentic Cantonese Dim Sums in SF"
  metaDescription: "Discover Dim Sum Club 點心薈 in San Francisco, CA, where traditional handmade Cantonese dim sums meet outstanding service. takeaway food or Order online now!" 
  keywords: ""
  img: ""
  thisPageUrl: ""
  locale: "en_US" # zh_TW | zh_CN
---
<!-- hello world -->