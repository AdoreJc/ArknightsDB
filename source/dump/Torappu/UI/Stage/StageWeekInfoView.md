# StageWeekInfoView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RectTransform _weekItemContainer`

- `GameObject _inactivePrefab`

- `GameObject _activePrefab`

- `GameObject _forceOpenPrefab`


## Methods

- `Void Rebuild(WeekStruct`1, GetOpenState`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageWeekInfoView : MonoBehaviour, IHotfixable
{
	protected RectTransform _weekItemContainer; // 0x18
	protected GameObject _inactivePrefab; // 0x20
	protected GameObject _activePrefab; // 0x28
	protected GameObject _forceOpenPrefab; // 0x30
	private static DelegateBridge __Hotfix0_Rebuild; // 0x0
	private static DelegateBridge __Hotfix0_InstCheck; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x VA: 0x0
	public Void Rebuild(WeekStruct`1 weekConfig, GetOpenState`1 openState) { }
	// RVA: 0x2fb19d4 VA: 0x75955c99d4
	public virtual Void InstCheck(ZoneOpenState isActiveFlag) { }
	// RVA: 0x2fb1960 VA: 0x75955c9960
	public Void .ctor() { }
}
```