# ArchiveFragmentInfoView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _panelUnattained`

- `Text _textName`

- `Text _textWeight`

- `SimpleLayoutContent _weightContent`

- `Text _textUsage`

- `Text _textDesc`

- `Image _imgIcon`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `Int32 m_cachedValue`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveFragmentInfoView : DataBinder`1, IHotfixable
{
	private TitleConfig[] _configList; // 0x20
	private GameObject[] _panelLocked; // 0x28
	private GameObject[] _panelUnlock; // 0x30
	private GameObject _panelUnattained; // 0x38
	private Text _textName; // 0x40
	private Text _textWeight; // 0x48
	private SimpleLayoutContent _weightContent; // 0x50
	private Text _textUsage; // 0x58
	private Text _textDesc; // 0x60
	private Image _imgIcon; // 0x68
	private Boolean m_hasInited; // 0x70
	private Adapter m_adapter; // 0x78
	private Int32 m_cachedValue; // 0x80
	private UIPageFinder m_pageFinder; // 0x88
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3054360 VA: 0x759566c360
	public override Void OnValueChanged(FragmentProperty property) { }
	// RVA: 0x30546b8 VA: 0x759566c6b8
	private Void _InitIfNot() { }
	// RVA: 0x305481c VA: 0x759566c81c
	public Void .ctor() { }
}
```