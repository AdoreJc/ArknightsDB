# CrisisLongTermShopView

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `SimpleLayoutContent _viewContainer`

- `CrisisShopEvent clickEvent`

- `GameObject _openBtn`

- `GameObject _wholeFoldBtn`

- `GameObject _foldBtn`

- `GameObject _softMaskImg`

- `ScrollRect _scrollRect`

- `GridLayoutGroup _layoutGroup`

- `Adapter m_adapter`

- `Boolean m_isInited`

- `Boolean m_isFoldAvail`

- `Tween m_cacheTweem`


## Methods

- `Void _InitIfNot()`

- `Void RenderData(List`1, Boolean, Boolean)`

- `Void _SetOpenWithoutRefresh()`

- `Void SetOpen()`

- `Void _SetFoldWithoutRefresh()`

- `Void SetFold()`

- `Void SetUnableToFold()`

- `Void OnValueChanged(Vector2)`

- `Single <SetFold>b__19_0()`

- `Void <SetFold>b__19_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisLongTermShopView : MonoBehaviour
{
	private const Int32 BOTTOM_FOLD; // 0x0
	private const Int32 BOTTOM_OPEN; // 0x0
	private SimpleLayoutContent _viewContainer; // 0x18
	public CrisisShopEvent clickEvent; // 0x20
	private GameObject _openBtn; // 0x28
	private GameObject _wholeFoldBtn; // 0x30
	private GameObject _foldBtn; // 0x38
	private GameObject _softMaskImg; // 0x40
	private ScrollRect _scrollRect; // 0x48
	private GridLayoutGroup _layoutGroup; // 0x50
	private Adapter m_adapter; // 0x58
	private Boolean m_isInited; // 0x60
	private Boolean m_isFoldAvail; // 0x61
	private Tween m_cacheTweem; // 0x68


	// RVA: 0x2c37a0c VA: 0x759524fa0c
	private Void _InitIfNot() { }
	// RVA: 0x2c37b18 VA: 0x759524fb18
	public Void RenderData(List`1 data, Boolean inSeason, Boolean isFirstTimeToRender) { }
	// RVA: 0x2c37cf0 VA: 0x759524fcf0
	private Void _SetOpenWithoutRefresh() { }
	// RVA: 0x2c37d7c VA: 0x759524fd7c
	public Void SetOpen() { }
	// RVA: 0x2c37be0 VA: 0x759524fbe0
	private Void _SetFoldWithoutRefresh() { }
	// RVA: 0x2c37db4 VA: 0x759524fdb4
	public Void SetFold() { }
	// RVA: 0x2c37c78 VA: 0x759524fc78
	public Void SetUnableToFold() { }
	// RVA: 0x2c37efc VA: 0x759524fefc
	public Void OnValueChanged(Vector2 pos) { }
	// RVA: 0x2c37ff0 VA: 0x759524fff0
	public Void .ctor() { }
	// RVA: 0x2c38000 VA: 0x7595250000
	private Single <SetFold>b__19_0() { }
	// RVA: 0x2c38024 VA: 0x7595250024
	private Void <SetFold>b__19_1(Single val) { }
}
```