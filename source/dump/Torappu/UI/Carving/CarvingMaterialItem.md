# CarvingMaterialItem

**Namespace:** `Torappu.UI.Carving`


## Fields

- `GameObject _materialBg`

- `Image _materialIcon`

- `GameObject _materialCntObj`

- `Text _materialCntTxt`

- `Int32 _cntTxtSizeSmall`

- `Int32 _cntTxtSizeBig`

- `UIPageFinder m_pageFinder`

- `String m_cachedIconId`

- `Single m_cachedScaler`


## Methods

- `Void Render(CarvingMaterialModel)`

- `Void SetScaler(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMaterialItem : MonoBehaviour, IHotfixable
{
	private const Int32 CNT_TEXT_SIZE_LIMIT_DIGIT; // 0x0
	private GameObject _materialBg; // 0x18
	private Image _materialIcon; // 0x20
	private GameObject _materialCntObj; // 0x28
	private Text _materialCntTxt; // 0x30
	private Int32 _cntTxtSizeSmall; // 0x38
	private Int32 _cntTxtSizeBig; // 0x3c
	private UIPageFinder m_pageFinder; // 0x40
	private String m_cachedIconId; // 0x50
	private Single m_cachedScaler; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_SetScaler; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2dbb9dc VA: 0x75953d39dc
	public Void Render(CarvingMaterialModel model) { }
	// RVA: 0x2dbb8dc VA: 0x75953d38dc
	public Void SetScaler(Single scaler) { }
	// RVA: 0x2dbfb28 VA: 0x75953d7b28
	public Void .ctor() { }
}
```