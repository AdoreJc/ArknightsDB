# Act9D0SubMissionItem

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `String _subMissionId`

- `GameObject _hasAllPart`

- `Image _fillAmount`

- `UIStringEvent _clickEvent`


## Properties

- `String subMissionId`


## Methods

- `String get_subMissionId()`

- `Void Render(SubMissionViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0SubMissionItem : MonoBehaviour, IHotfixable
{
	private String _subMissionId; // 0x18
	private GameObject _hasAllPart; // 0x20
	private Image _fillAmount; // 0x28
	private UIStringEvent _clickEvent; // 0x30
	private static DelegateBridge __Hotfix0_get_subMissionId; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String subMissionId { get; }

	// RVA: 0x31ab81c VA: 0x75957c381c
	public String get_subMissionId() { }
	// RVA: 0x31ab884 VA: 0x75957c3884
	public Void Render(SubMissionViewModel viewModel) { }
	// RVA: 0x31ab964 VA: 0x75957c3964
	public Void OnClick() { }
	// RVA: 0x31aba1c VA: 0x75957c3a1c
	public Void .ctor() { }
}
```