# ActVecBreakOffenseBattleFinishCharCardHolder

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `ActVecBreakOffenseBattleFinishCharCardView m_CardViewView`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot(ActVecBreakOffenseBattleFinishCharCardView)`

- `Void Render(SquadItemStruct, ActVecBreakOffenseBattleFinishCharCardView, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class ActVecBreakOffenseBattleFinishCharCardHolder : MonoBehaviour, IHotfixable
{
	private ActVecBreakOffenseBattleFinishCharCardView m_CardViewView; // 0x18
	private Boolean m_isInited; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22c70e8 VA: 0x75948df0e8
	private Void _InitIfNot(ActVecBreakOffenseBattleFinishCharCardView prefab) { }
	// RVA: 0x22c67dc VA: 0x75948de7dc
	public Void Render(SquadItemStruct squadItemStructs, ActVecBreakOffenseBattleFinishCharCardView prefab, Boolean isAssist) { }
	// RVA: 0x22c78c4 VA: 0x75948df8c4
	public Void .ctor() { }
}
```