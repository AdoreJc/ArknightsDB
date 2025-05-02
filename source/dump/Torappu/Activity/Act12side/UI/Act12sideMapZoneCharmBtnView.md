# Act12sideMapZoneCharmBtnView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `GameObject _objBtnCharmRoom`

- `GameObject _objLockCharmRoom`

- `GameObject _objNew`

- `GameObject _objReuse`

- `Text _txtCharmRoomLock`

- `Action m_onCharmBtnClick`


## Methods

- `Void Init(Action)`

- `Void EventOnCharmBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMapZoneCharmBtnView : MonoBehaviour, IHotfixable
{
	private GameObject _objBtnCharmRoom; // 0x18
	private GameObject _objLockCharmRoom; // 0x20
	private GameObject _objNew; // 0x28
	private GameObject _objReuse; // 0x30
	private Text _txtCharmRoomLock; // 0x38
	private Action m_onCharmBtnClick; // 0x40
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_EventOnCharmBtnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3463cfc VA: 0x7595a7bcfc
	public Void Init(Action onBtnClick) { }
	// RVA: 0x3463d80 VA: 0x7595a7bd80
	public Void EventOnCharmBtnClick() { }
	// RVA: 0x3463e04 VA: 0x7595a7be04
	public Void .ctor() { }
}
```