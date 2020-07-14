# GrBarcode(temp)
Recognize the barcode And Note Infomation. This App for blind 


# 1. Introduction
## 1.1 Purpose
When blind people buy some goods, It's hard to roconize which one is favorate or hate.
Even there are braille. There is only basic infomation like 'Drinks'
This app support recognizing goods by reading barcode.

## 1.2 Scope
The purpose of the application is to make things easier to recognize.
Use the camera to find a barcode for a product and to notify you of product information 
The application runs on Android smartphones.

## 1.3 Assumptions and Dependencies
 - Operating System: The application will be developed for Android platforms
   * Android 8.0.0 and upper versions. 
             (  Wi-Fi Direct should be supported.When download database
                Camera should be supported.)
 - Accessablity : The application should support the provision of non-visible information for the blind 
                  ( Such as current state, action result, etc )
These assumptions may change during the implementation and new features may be
added. 


# 2. Overall Description

## 2.1 Product functions
  
  - Image input from camera.(permission require)
     Open our application, Application read picture from devise's camaera.
     
  - Recognize barcode from Image
     Recognize barcode from image.
     
  - Read barcode
     barcode turn to number
     
  - Read QRcode(Subsequent)
     turn to infomation

  - Turn jancode to infomation
     Turn jancode(from barcode) readable infomation

## 2.2 User Needs
1. Current state will provide with non-visible infomation
2. get goods infomatrion from barcode


# 3. System Features and Requirements

## 3.1 Functional Requirements
1. Nofity current state of screen by sounds effect
2. When captured barcode. Nofity current state by sounds effect
3. Read goods informatrion by Using TTS.
4. For blind, Double tab is screen action. One tab is selected button's infomation

## 3.2 External Interface Requirements
1. Target android system is Oreo(8.0) or higher
2. The device needs camera for reading barcode
3. The device needs network device for getting product data
