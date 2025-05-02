# ActivityCommonFavorUpEntryView

**Namespace:** `Torappu.Activity`


## Fields

- `GameObject _favorUpPanelGo`

- `GameObject _emptyPanelGo`

- `UICommonTrackPoint _favorUpTrackPoint`


## Properties

- `UICommonTrackPoint favorUpTrackPoint`


## Methods

- `UICommonTrackPoint get_favorUpTrackPoint()`

- `Void UpdateView(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCommonFavorUpEntryView : MonoBehaviour, IHotfixable
{
	private GameObject _favorUpPanelGo; // 0x18
	private GameObject _emptyPanelGo; // 0x20
	private UICommonTrackPoint _favorUpTrackPoint; // 0x28
	private static DelegateBridge __Hotfix0_get_favorUpTrackPoint; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public UICommonTrackPoint favorUpTrackPoint { get; }

	// RVA: 0x30c5b00 VA: 0x75956ddb00
	public UICommonTrackPoint get_favorUpTrackPoint() { }
	// RVA: 0x30c5b68 VA: 0x75956ddb68
	public Void UpdateView(List`1 favorUpList) { }
	// RVA: 0x30c5c2c VA: 0x75956ddc2c
	public Void .ctor() { }
}
```