# Act3D0ClueSliderObj

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `GameObject _selectedPart`

- `GameObject _availPart`

- `GameObject _unavailPart`

- `Int32 m_currentIndex`

- `State m_cacheState`


## Methods

- `Void InitData(Int32, Act3D0ClueInfo)`

- `Void SetIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0ClueSliderObj : MonoBehaviour, IHotfixable
{
	private GameObject _selectedPart; // 0x18
	private GameObject _availPart; // 0x20
	private GameObject _unavailPart; // 0x28
	private Int32 m_currentIndex; // 0x30
	private State m_cacheState; // 0x34
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_SetIndex; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3239814 VA: 0x7595851814
	public Void InitData(Int32 index, Act3D0ClueInfo info) { }
	// RVA: 0x32398a4 VA: 0x75958518a4
	public Void SetIndex(Int32 index) { }
	// RVA: 0x3239988 VA: 0x7595851988
	public Void .ctor() { }
}
```