# AVGTutorialFocus

**Namespace:** `Torappu.AVG`


## Fields

- `RectTransform _focusRect`

- `Single _defaultFadeTime`

- `GameObject _circleStyle`

- `Single _extraScale`

- `GameObject _highlightCircleStyle`

- `GameObject _highlightCircleObj`

- `GameObject _highlightRectStyle`

- `GameObject _highlightRectObj`

- `CanvasGroup m_group`


## Methods

- `CanvasGroup _GetCanvasGroup()`

- `Void OnReset()`

- `Void SetFocus(Style, Vector2, Vector2, Single, AnchorType)`

- `Void Hide()`

- `Void _SetCircle(Vector2)`

- `Void _SetHighlightCircle(Vector2)`

- `Void _SetHighlightRect(Vector2)`

- `Void _RefreshBlackMasks()`

- `Void <>xLuaBaseProxy_OnRectTransformDimensionsChange()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGTutorialFocus : UIBehaviour, IHotfixable
{
	private RectTransform _focusRect; // 0x18
	private Single _defaultFadeTime; // 0x20
	private GameObject _circleStyle; // 0x28
	private Single _extraScale; // 0x30
	private GameObject _highlightCircleStyle; // 0x38
	private GameObject _highlightCircleObj; // 0x40
	private GameObject _highlightRectStyle; // 0x48
	private GameObject _highlightRectObj; // 0x50
	private UICustomAnchor[] _blackMasks; // 0x58
	private CanvasGroup m_group; // 0x60
	private static DelegateBridge __Hotfix0__GetCanvasGroup; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_SetFocus; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge __Hotfix0__SetCircle; // 0x20
	private static DelegateBridge __Hotfix0__SetHighlightCircle; // 0x28
	private static DelegateBridge __Hotfix0__SetHighlightRect; // 0x30
	private static DelegateBridge __Hotfix0__RefreshBlackMasks; // 0x38
	private static DelegateBridge __Hotfix0_OnRectTransformDimensionsChange; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3ead300 VA: 0x75964c5300
	private CanvasGroup _GetCanvasGroup() { }
	// RVA: 0x3ead3d8 VA: 0x75964c53d8
	public Void OnReset() { }
	// RVA: 0x3ead4d0 VA: 0x75964c54d0
	public Void SetFocus(Style style, Vector2 position, Vector2 size, Single black, AnchorType anchor) { }
	// RVA: 0x3eada30 VA: 0x75964c5a30
	public Void Hide() { }
	// RVA: 0x3ead754 VA: 0x75964c5754
	private Void _SetCircle(Vector2 size) { }
	// RVA: 0x3ead834 VA: 0x75964c5834
	private Void _SetHighlightCircle(Vector2 size) { }
	// RVA: 0x3ead8ec VA: 0x75964c58ec
	private Void _SetHighlightRect(Vector2 size) { }
	// RVA: 0x3ead984 VA: 0x75964c5984
	private Void _RefreshBlackMasks() { }
	// RVA: 0x3eadba4 VA: 0x75964c5ba4
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x3eadc44 VA: 0x75964c5c44
	public Void .ctor() { }
	// RVA: 0x3eadccc VA: 0x75964c5ccc
	private Void <>xLuaBaseProxy_OnRectTransformDimensionsChange() { }
}
```