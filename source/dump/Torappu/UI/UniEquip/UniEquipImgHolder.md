# UniEquipImgHolder

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `GameObject _initPart`

- `GameObject _additivePart`

- `Image _initEquipSubProfessionIcon`

- `Image _initEquipPic`

- `Image _additiveEquipPic`

- `UIColorGraphic _colorGraphic`

- `UIScaler _scaler`

- `Color _lockColor`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(UniEquipData, String, Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipImgHolder : MonoBehaviour, IHotfixable
{
	private GameObject _initPart; // 0x18
	private GameObject _additivePart; // 0x20
	private Image _initEquipSubProfessionIcon; // 0x28
	private Image _initEquipPic; // 0x30
	private Image _additiveEquipPic; // 0x38
	private UIColorGraphic _colorGraphic; // 0x40
	private UIScaler _scaler; // 0x48
	private Color _lockColor; // 0x50
	private UIPageFinder m_pageFinder; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x22ff4fc VA: 0x75949174fc
	public Void Render(UniEquipData data, String subProfessionId, Boolean isUnlock, Single scaler) { }
	// RVA: 0x22ff6ec VA: 0x75949176ec
	public Void .ctor() { }
}
```