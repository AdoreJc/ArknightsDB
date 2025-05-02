# Act1VAutoChessEntryAnimView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Boolean m_isInited`

- `Int32 m_cachedAnimSeq`

- `Int32 m_cachedFastModeSeq`

- `ShowType m_lastShowType`

- `ShowType m_curShowType`


## Properties

- `Boolean isPlaying`


## Methods

- `Boolean get_isPlaying()`

- `Void Render(Act1VAutoChessEntryViewModel)`

- `Void EnsureSubViewAnim(ShowType, List`1)`

- `Void _InitIfNot()`

- `Void _SampleAnimationToInitState()`

- `Sequence _GetCombinedTweenFromAnimHolders(List`1, Boolean, Boolean, Ease)`

- `Void _HandleShowType(ShowType, ShowType, Boolean)`

- `StateNodeType _GetStateNodeByViewShowType(ShowType)`

- `Tween <_InitIfNot>b__12_0()`

- `Tween <_InitIfNot>b__12_1()`

- `Tween <_InitIfNot>b__12_2()`

- `Tween <_InitIfNot>b__12_3()`

- `Tween <_InitIfNot>b__12_4()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryAnimView : MonoBehaviour, IHotfixable
{
	private Boolean m_isInited; // 0x18
	private Int32 m_cachedAnimSeq; // 0x1c
	private Int32 m_cachedFastModeSeq; // 0x20
	private EnumIntDictionary`2 m_subViewAnimHolderDatas; // 0x28
	private UIStateTransitionTween`1 m_transitionStateMachine; // 0x30
	private ShowType m_lastShowType; // 0x38
	private ShowType m_curShowType; // 0x3c
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_EnsureSubViewAnim; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__SampleAnimationToInitState; // 0x20
	private static DelegateBridge __Hotfix0__GetCombinedTweenFromAnimHolders; // 0x28
	private static DelegateBridge __Hotfix0__HandleShowType; // 0x30
	private static DelegateBridge __Hotfix0__GetStateNodeByViewShowType; // 0x38
	private static DelegateBridge __Hotfix0__GetAnimHolderByShowType; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean isPlaying { get; }

	// RVA: 0x3333a78 VA: 0x759594ba78
	public Boolean get_isPlaying() { }
	// RVA: 0x333ba4c VA: 0x7595953a4c
	public Void Render(Act1VAutoChessEntryViewModel viewModel) { }
	// RVA: 0x333bf14 VA: 0x7595953f14
	public Void EnsureSubViewAnim(ShowType showType, List`1 holders) { }
	// RVA: 0x333bb78 VA: 0x7595953b78
	private Void _InitIfNot() { }
	// RVA: 0x333bfd4 VA: 0x7595953fd4
	private Void _SampleAnimationToInitState() { }
	// RVA: 0x333c1a0 VA: 0x75959541a0
	private Sequence _GetCombinedTweenFromAnimHolders(List`1 holders, Boolean isEnter, Boolean isInverse, Ease easeType) { }
	// RVA: 0x333be44 VA: 0x7595953e44
	private Void _HandleShowType(ShowType fromShowType, ShowType toShowType, Boolean isFastMode) { }
	// RVA: 0x333c3d0 VA: 0x75959543d0
	private StateNodeType _GetStateNodeByViewShowType(ShowType showType) { }
	// RVA: 0x333c0f8 VA: 0x75959540f8
	private List`1 _GetAnimHolderByShowType(ShowType showType) { }
	// RVA: 0x333c4e8 VA: 0x75959544e8
	public Void .ctor() { }
	// RVA: 0x333c5ac VA: 0x75959545ac
	private Tween <_InitIfNot>b__12_0() { }
	// RVA: 0x333c6d4 VA: 0x75959546d4
	private Tween <_InitIfNot>b__12_1() { }
	// RVA: 0x333c700 VA: 0x7595954700
	private Tween <_InitIfNot>b__12_2() { }
	// RVA: 0x333c858 VA: 0x7595954858
	private Tween <_InitIfNot>b__12_3() { }
	// RVA: 0x333c9b0 VA: 0x75959549b0
	private Tween <_InitIfNot>b__12_4() { }
}
```