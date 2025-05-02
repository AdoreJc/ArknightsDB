# Act1ArcadeGameObjectSwitchComp

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `GameObject m_catchedGo`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void SwitchByIndex(Int32, OutOfRangeLogicType)`

- `Boolean _HandleIndex(Int32, OutOfRangeLogicType, out)`

- `Void HideAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeGameObjectSwitchComp : MonoBehaviour, IHotfixable
{
	private GameObject[] _objects; // 0x18
	private GameObject m_catchedGo; // 0x20
	private Boolean m_isInited; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_SwitchByIndex; // 0x8
	private static DelegateBridge __Hotfix0__HandleIndex; // 0x10
	private static DelegateBridge __Hotfix0_HideAll; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3412f3c VA: 0x7595a2af3c
	private Void _InitIfNot() { }
	// RVA: 0x341308c VA: 0x7595a2b08c
	public Void SwitchByIndex(Int32 index, OutOfRangeLogicType outOfRangeLogicType) { }
	// RVA: 0x341322c VA: 0x7595a2b22c
	private Boolean _HandleIndex(Int32 index, OutOfRangeLogicType outOfRangeLogicType, out Int32 newIndex) { }
	// RVA: 0x3412fc0 VA: 0x7595a2afc0
	public Void HideAll() { }
	// RVA: 0x3413338 VA: 0x7595a2b338
	public Void .ctor() { }
}
```