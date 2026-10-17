# Img16DatSer
Headerless 16-bit Images DataSeries Viewer (MFC-application); for Windows and Ubuntu+Wine)

= Image format(s):
  16-bit little-endian (signed, unsigned) without header, 

= The executables
  - Img16DatSer.exe
   Windows GUI (supports variable modes of StretchBlt).
   
  - Img16DatSerDX2.exe
    Windows DX2 (only StretchBlt=halftone); 
    <might> work ~visibly faster in older Linux-machines.

= Specific features for "comprehend and analysis" of data-series
  - profile-gutter auto-synchronized with image-view (by spatial location and grayscale)
  - easy resize/zoom and  "copy" of visible area to clipboard

= License and statements:
  - License : MIT
  - This application incapsulates a trivia subset of functions in V i e w 1 6 (in commercial SDK V a t e c h R a y e n c e V a D a v).
  - This application excludes "non-trivia" functionalities (such as "differential view", "directional-blur").
  - Used sources are: 
    -- K&R C RTL, MFC VS 2008, Wikipedia;
    -- exclusively trivial personal-free-time-made source-code. 
  - Beside enlisted above, here is no single explicit (and perhaps implicit) code-snippetfrom another person or organization.

= Source code: in the neighboring github's repository (might need a request to access).

= The purpose of this repository is to gather occasional test of standard GUI-functionalities
  (especially under WinE: copy/paste, winebrowser, graphic's correctness under Wayland).
