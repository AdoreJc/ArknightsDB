# FifthAnnivExploreMissionObjHolder

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreMissionObjView _view`

- `Button _collectAllBtn`

- `UIStringEvent _onMissionObjClicked`

- `UIStringEvent _onCollectAllBtnClicked`


## Methods

- `Void Render(MissionObjHolderViewModel)`

- `Void RegisCollectAll(UIStringEvent)`

- `Void RegisMissionObjClicked(UIStringEvent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMissionObjHolder : MonoBehaviour, IHotfixable
{
	private FifthAnnivExploreMissionObjView _view; // 0x18
	private Button _collectAllBtn; // 0x20
	private UIStringEvent _onMissionObjClicked; // 0x28
	private UIStringEvent _onCollectAllBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RegisCollectAll; // 0x8
	private static DelegateBridge __Hotfix0_RegisMissionObjClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x292c930 VA: 0x7594f44930
	public Void Render(MissionObjHolderViewModel viewModel) { }
	// RVA: 0x292ca1c VA: 0x7594f44a1c
	public Void RegisCollectAll(UIStringEvent e) { }
	// RVA: 0x292cb38 VA: 0x7594f44b38
	public Void RegisMissionObjClicked(UIStringEvent e) { }
	// RVA: 0x292cc5c VA: 0x7594f44c5c
	public Void .ctor() { }
}
```