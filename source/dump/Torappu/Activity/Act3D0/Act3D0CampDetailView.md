# Act3D0CampDetailView

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `UIBlurFloatPanel _floatPanel`

- `Text _textName`

- `Text _textCampDesc`

- `Text _textRewardDesc`

- `Act3D0CampViewModel m_campModel`

- `Action onCampCancelled`


## Methods

- `Void Open(Act3D0CampViewModel)`

- `IEnumerator CloseCoroutine()`

- `Void _Render()`

- `Void EventOnConfirmClicked()`

- `Void EventOnCancelClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0CampDetailView : MonoBehaviour, IHotfixable
{
	private UIBlurFloatPanel _floatPanel; // 0x18
	private CampImage[] _campImages; // 0x20
	private Text _textName; // 0x28
	private Text _textCampDesc; // 0x30
	private Text _textRewardDesc; // 0x38
	private Act3D0CampViewModel m_campModel; // 0x40
	public Action`1 onCampConfirmed; // 0x48
	public Action onCampCancelled; // 0x50
	private static DelegateBridge __Hotfix0_Open; // 0x0
	private static DelegateBridge __Hotfix0_CloseCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3236cac VA: 0x759584ecac
	public Void Open(Act3D0CampViewModel campModel) { }
	// RVA: 0x3236f44 VA: 0x759584ef44
	public IEnumerator CloseCoroutine() { }
	// RVA: 0x3236d70 VA: 0x759584ed70
	private Void _Render() { }
	// RVA: 0x3237018 VA: 0x759584f018
	public Void EventOnConfirmClicked() { }
	// RVA: 0x32370a8 VA: 0x759584f0a8
	public Void EventOnCancelClicked() { }
	// RVA: 0x3237154 VA: 0x759584f154
	public Void .ctor() { }
}
```