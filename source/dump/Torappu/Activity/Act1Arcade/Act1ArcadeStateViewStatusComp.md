# Act1ArcadeStateViewStatusComp

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `RectTransform _viewRoot`

- `Act1ArcadeStateStatusBaseView m_curView`


## Methods

- `Void ChangeToState(Type)`

- `Void OnStatePreResume(Type, Boolean)`

- `Void OnStateResume(Type, Boolean)`

- `Act1ArcadeStateStatusBaseView RegisterView(String, String, ILoadAsset)`

- `Void HideAllView()`

- `Void _SetAsCurView(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStateViewStatusComp : PageSingleComponent
{
	private RectTransform _viewRoot; // 0x20
	private Dictionary`2 m_viewDict; // 0x28
	private Act1ArcadeStateStatusBaseView m_curView; // 0x30
	private static DelegateBridge __Hotfix0_ChangeToState; // 0x0
	private static DelegateBridge __Hotfix0_OnStatePreResume; // 0x8
	private static DelegateBridge __Hotfix0_OnStateResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterView; // 0x18
	private static DelegateBridge __Hotfix0_HideAllView; // 0x20
	private static DelegateBridge __Hotfix0__SetAsCurView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x33ecf70 VA: 0x7595a04f70
	public Void ChangeToState(Type stateType) { }
	// RVA: 0x33ed034 VA: 0x7595a05034
	public Void OnStatePreResume(Type stateType, Boolean isFromStack) { }
	// RVA: 0x33ed15c VA: 0x7595a0515c
	public Void OnStateResume(Type stateType, Boolean isFromStack) { }
	// RVA: 0x VA: 0x0
	public Act1ArcadeStateStatusBaseView RegisterView(String actId, String prefabId, ILoadAsset assetLoader) { }
	// RVA: 0x33ee008 VA: 0x7595a06008
	private Void HideAllView() { }
	// RVA: 0x33ee0cc VA: 0x7595a060cc
	private Void _SetAsCurView(Type stateType) { }
	// RVA: 0x33ee1ec VA: 0x7595a061ec
	public Void .ctor() { }
}
```