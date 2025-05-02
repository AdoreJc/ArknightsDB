# ActVecBreakOffenseBattleFinishResultBuffView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `GameObject _lockPartGo`

- `GameObject _normalPartGo`

- `ActVecBreakOffenseBattleFinishResultBuffItemView _buffItemPrefab`

- `Boolean m_isinited`


## Methods

- `Void _InitIfNot()`

- `Void Render(ActVecBreakOffenseBattleFinishViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class ActVecBreakOffenseBattleFinishResultBuffView : MonoBehaviour, IHotfixable
{
	private GameObject _lockPartGo; // 0x18
	private GameObject _normalPartGo; // 0x20
	private ActVecBreakOffenseBattleFinishResultBuffItemView _buffItemPrefab; // 0x28
	private List`1 _buffItemRoots; // 0x30
	private List`1 m_buffItemViews; // 0x38
	private Boolean m_isinited; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22c57e0 VA: 0x75948dd7e0
	private Void _InitIfNot() { }
	// RVA: 0x22c5ab4 VA: 0x75948ddab4
	public Void Render(ActVecBreakOffenseBattleFinishViewModel viewModel) { }
	// RVA: 0x22c5c2c VA: 0x75948ddc2c
	public Void .ctor() { }
}
```