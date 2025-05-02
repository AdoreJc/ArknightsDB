# Act36sideZoneMapContainerFocusView

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `Image _cardImg`

- `RectTransform _frontAnimContainer`

- `Act36sideZoneFocusAnimView _animView`

- `Int32 m_cachedFocusIndex`

- `Act36sideZoneFocusAnimView m_frontAnimView`


## Methods

- `Void RenderStable(Int32, Act36sideZoneMapCardBackView, Act36sideZoneFocusAnimView, Boolean)`

- `Void RenderUnStable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideZoneMapContainerFocusView : MonoBehaviour, IHotfixable
{
	private Image _cardImg; // 0x18
	private RectTransform _frontAnimContainer; // 0x20
	private Act36sideZoneFocusAnimView _animView; // 0x28
	private Int32 m_cachedFocusIndex; // 0x30
	private Act36sideZoneFocusAnimView m_frontAnimView; // 0x38
	private static DelegateBridge __Hotfix0_RenderStable; // 0x0
	private static DelegateBridge __Hotfix0_RenderUnStable; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3250108 VA: 0x7595868108
	public Void RenderStable(Int32 focusIndex, Act36sideZoneMapCardBackView cardBackView, Act36sideZoneFocusAnimView animViewPrefab, Boolean fastMode) { }
	// RVA: 0x3250350 VA: 0x7595868350
	public Void RenderUnStable() { }
	// RVA: 0x3250424 VA: 0x7595868424
	public Void .ctor() { }
}
```