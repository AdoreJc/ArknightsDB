# SandboxV2HomeMonthEntryView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `TwoStateToggle _validToggle`

- `Text _disableLabel`

- `GameObject _fullstoreNode`

- `GameObject _fullstoreCompleteNode`

- `GameObject _updateNode`

- `GameObject _updateCompleteNode`

- `Text _updateCDLabel`

- `Text _remainCDLabel`


## Methods

- `Void Render(SandboxV2HomeModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2HomeMonthEntryView : MonoBehaviour, IHotfixable
{
	public TwoStateToggle _validToggle; // 0x18
	private Text _disableLabel; // 0x20
	private GameObject _fullstoreNode; // 0x28
	private GameObject _fullstoreCompleteNode; // 0x30
	private Text[] _rushCountLabels; // 0x38
	private Text[] _rushDoneCntLabels; // 0x40
	private GameObject _updateNode; // 0x48
	private GameObject _updateCompleteNode; // 0x50
	private Text _updateCDLabel; // 0x58
	private Text _remainCDLabel; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25d7e58 VA: 0x7594befe58
	public Void Render(SandboxV2HomeModel model) { }
	// RVA: 0x25d82ac VA: 0x7594bf02ac
	public Void .ctor() { }
}
```