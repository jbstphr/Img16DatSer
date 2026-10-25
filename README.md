# Img16DatSer
Headerless 16-bit Images DataSeries Viewer (MFC-application); for Windows and Ubuntu+Wine).
Trivia and basic functionalities that absent in ~ImageJ.

= Image format(s):
  16-bit little-endian (signed, unsigned) without header 

= The executables
  - Img16DatSer.exe
    Windows GUI (supports variable modes of StretchBlt).
   
  - Img16DatSerDX2.exe
    Windows DX2 (only StretchBlt=halftone); 
    <might> work ~visibly faster in older Linux-machines.

= Specific features for "comprehend and analysis" of data-series
  - Profile-gutter auto-synchronized with image-view (by spatial location and grayscale);
This UI gives ordinary person a chance to evaluate "image's information in ~Shannon's definition" such logically as professional radiologist (whose eyes distinguish ~>100 gray_levels) does. 
  - Natively debugged with WinE (executes Nautilus-file-manager, copies via WinE/Linux clipboard).

= Formal documentation:
  _Img16DatSer.pdf (it the text of built-in help with sketches and screenshots).
  
= License and statements:
  - License : MIT (for binaries, configs, menus, documents)
  - Used sources are: 
    - K&R C RTL, MFC VS 2008, Wikipedia;
    - exclusively trivial personal-free-time-made source-code. 
  - Beside enlisted above, here is no single explicit (and perhaps implicit) code-snippetfrom another person or organization.
  - This application shares a trivia-subset of functionalities with existing X-Ray SDK.
  - This application excludes all "non-trivia" functionalities (such as "differential view", "directional-blur", "spatial-filters").

= The purpose of this repository is to gather occasional test of standard GUI-functionalities
  (especially under WinE: copy/paste, winebrowser, graphic's correctness under Wayland). For mutual benefits:
  - a user might have practical functionalities that absent in ~ImageJ (though being trivia and basic);
  - the developer might use the reviews in further applications (including commercial code).

= Source code: in the neighboring github's repository (might need a request to access).
"https://github.com/jbstphr/Img16DatSer_Src"
