# UIManager

**Namespace:** `HGSDK.UI`


## Fields

- `Options m_options`

- `UIPage m_currentPage`

- `RaycastBlockerMgr m_raycastBlockerMgr`

- `HGSDK <sdk>k__BackingField`


## Properties

- `Boolean isShownUI`

- `HGSDK sdk`


## Methods

- `Boolean get_isShownUI()`

- `HGSDK get_sdk()`

- `Void set_sdk(HGSDK)`

- `Void OnStart()`

- `PageType OpenUIPage(PageType, Action`1)`

- `Boolean CloseUIPage(UIPage)`

- `Boolean CloseCurrentUIPage()`

- `Boolean BlockRaycast(Boolean, RaycastBlockerSource)`

- `IEnumerator _DoOpenUICoroutine()`

- `IEnumerator _DoCloseUICoroutine()`

- `Void _UpdateViews()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class UIManager
{
	private Options m_options; // 0x10
	private UIPage m_currentPage; // 0x30
	private RaycastBlockerMgr m_raycastBlockerMgr; // 0x38
	private HGSDK <sdk>k__BackingField; // 0x40

	public Boolean isShownUI { get; }
	public HGSDK sdk { get; set; }

	// RVA: 0x3565030 VA: 0x7595b7d030
	public Boolean get_isShownUI() { }
	// RVA: 0x3565090 VA: 0x7595b7d090
	public HGSDK get_sdk() { }
	// RVA: 0x3565098 VA: 0x7595b7d098
	private Void set_sdk(HGSDK value) { }
	// RVA: 0x35650a0 VA: 0x7595b7d0a0
	public Void .ctor(HGSDK sdk, Options options) { }
	// RVA: 0x35651d0 VA: 0x7595b7d1d0
	public Void OnStart() { }
	// RVA: 0x VA: 0x0
	public PageType OpenUIPage(PageType uiPrefab, Action`1 onLoaded) { }
	// RVA: 0x355dec0 VA: 0x7595b75ec0
	public Boolean CloseUIPage(UIPage ui) { }
	// RVA: 0x35652d8 VA: 0x7595b7d2d8
	public Boolean CloseCurrentUIPage() { }
	// RVA: 0x3565370 VA: 0x7595b7d370
	public Boolean BlockRaycast(Boolean isBlock, RaycastBlockerSource source) { }
	// RVA: 0x35653c0 VA: 0x7595b7d3c0
	private IEnumerator _DoOpenUICoroutine() { }
	// RVA: 0x3565264 VA: 0x7595b7d264
	private IEnumerator _DoCloseUICoroutine() { }
	// RVA: 0x35651d4 VA: 0x7595b7d1d4
	private Void _UpdateViews() { }
}
```