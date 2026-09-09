# Rotating Image Studio v0.3

A PySide6 image and text composition studio inspired by the Blender/graphics-editor workflow.

## v0.3 features

- Image layers
- Text layers
- All images and text are draggable
- Corner handles resize images and text
- Rotation through Properties
- Scale through Properties
- Opacity
- Visibility
- Double-click text to edit
- Text font family, size, bold and italic
- Layer ordering:
  - Bring Forward
  - Send Backward
  - Bring to Front
  - Send to Back
- Duplicate / Delete
- Outliner with front-to-back ordering
- Save/Open `.ris` projects
- Canvas zoom
- Dark modern PySide6 interface

## Run on Windows PowerShell

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m rotating_image_studio
```

If PowerShell activation is restricted:

```powershell
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m rotating_image_studio
```

## Run tests

```powershell
python -m pytest
```

## Important

v0.3 focuses on composition and object manipulation. Video rendering/timeline features should be restored and expanded after the composition engine is stable.
