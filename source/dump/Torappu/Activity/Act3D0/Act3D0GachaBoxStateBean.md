# Act3D0GachaBoxStateBean

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `String defaultBoxId`

- `String m_actId`

- `String m_faction`


## Properties

- `Act3D0Data act3d0Data`


## Methods

- `Act3D0Data get_act3d0Data()`

- `Int32 CheckRemainCount(String, String, PlayerAct3D0Activity, Int32)`

- `Boolean CheckBoxInfi(String)`

- `Void InitInfo(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0GachaBoxStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public Dictionary`2 percent; // 0x18
	public List`1 gachaBoxInfo; // 0x20
	public String defaultBoxId; // 0x28
	private String m_actId; // 0x30
	private String m_faction; // 0x38
	private static DelegateBridge __Hotfix0_get_act3d0Data; // 0x0
	private static DelegateBridge __Hotfix0_CheckRemainCount; // 0x8
	private static DelegateBridge __Hotfix0_CheckBoxInfi; // 0x10
	private static DelegateBridge __Hotfix0_InitInfo; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Act3D0Data act3d0Data { get; }

	// RVA: 0x3239e70 VA: 0x7595851e70
	public Act3D0Data get_act3d0Data() { }
	// RVA: 0x3239ed4 VA: 0x7595851ed4
	public Int32 CheckRemainCount(String boxId, String goodId, PlayerAct3D0Activity actInfo, Int32 defaultValue) { }
	// RVA: 0x3239ff4 VA: 0x7595851ff4
	public Boolean CheckBoxInfi(String boxId) { }
	// RVA: 0x323a108 VA: 0x7595852108
	public Void InitInfo(String actId) { }
	// RVA: 0x323ade8 VA: 0x7595852de8
	public Void .ctor() { }
}
```