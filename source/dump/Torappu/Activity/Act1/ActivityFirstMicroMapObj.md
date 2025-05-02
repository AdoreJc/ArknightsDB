# ActivityFirstMicroMapObj

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `Text _textTitle`

- `Text _zoneIndex`

- `GameObject _selected`

- `String m_cacheZoneId`

- `UIStringEvent stringEvent`


## Methods

- `Void InitData(DefaultZoneData)`

- `Boolean SelectState(String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstMicroMapObj : MonoBehaviour, IHotfixable
{
	private Text _textTitle; // 0x18
	private Text _zoneIndex; // 0x20
	private GameObject _selected; // 0x28
	private String m_cacheZoneId; // 0x30
	public UIStringEvent stringEvent; // 0x38
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_SelectState; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3490d14 VA: 0x7595aa8d14
	public Void InitData(DefaultZoneData zoneData) { }
	// RVA: 0x3490dec VA: 0x7595aa8dec
	public Boolean SelectState(String selectedId) { }
	// RVA: 0x3490e88 VA: 0x7595aa8e88
	public Void OnClick() { }
	// RVA: 0x3490f1c VA: 0x7595aa8f1c
	public Void .ctor() { }
}
```