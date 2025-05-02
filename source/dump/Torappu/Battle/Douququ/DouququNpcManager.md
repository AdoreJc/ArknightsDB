# DouququNpcManager

**Namespace:** `Torappu.Battle.Douququ`


## Fields

- `Boolean m_hasChooseNpc`

- `DouququGameMode m_gameMode`

- `Act5FunNpcChoice m_lastChoice`


## Methods

- `Void Init(DouququGameMode)`

- `Void BeforeBetAppear()`

- `Void OnRoundEnd(RoundResult)`

- `Boolean TryGetSelectorInfo(Act5FunNpcSelector, out)`

- `Void _ProcessNpcInfoData()`

- `Void _ProcessNpcSelectorData()`

- `Void _ChooseNpc()`

- `Void _CalculateNpcScore()`

- `Act5FunNpcChoice _CalculateDefaultStrategy(Act5FunNpcData)`

- `Act5FunNpcChoice _CalculateChooseWinStrategy(String)`

- `Act5FunNpcChoice _CalculateChooseOddStrategy(String)`

- `Act5FunNpcChoice _CalculateFollowStrategy(String, Boolean)`

- `Void _SetNpcChoiceResult(RoundResult)`

- `Void _LogRoundNpcResult()`

- `Void _SetTeamList()`

- `Int32 <_ChooseNpc>b__17_0(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Douququ
public class DouququNpcManager : IHotfixable
{
	private Boolean m_hasChooseNpc; // 0x10
	private DouququGameMode m_gameMode; // 0x18
	private readonly List`1 m_npcWithWeights; // 0x20
	private readonly Dictionary`2 m_npcSelectorData; // 0x28
	private Dictionary`2 m_npcInfoData; // 0x30
	private readonly List`1 m_chooseRightNpcList; // 0x38
	private readonly List`1 m_chooseLeftNpcList; // 0x40
	private readonly List`1 m_npcChoiceList; // 0x48
	private List`1 m_npcSortList; // 0x50
	private Act5FunNpcChoice m_lastChoice; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_BeforeBetAppear; // 0x8
	private static DelegateBridge __Hotfix0_OnRoundEnd; // 0x10
	private static DelegateBridge __Hotfix0_GetNpcList; // 0x18
	private static DelegateBridge __Hotfix0_TryGetSelectorInfo; // 0x20
	private static DelegateBridge __Hotfix0__ProcessNpcInfoData; // 0x28
	private static DelegateBridge __Hotfix0__ProcessNpcSelectorData; // 0x30
	private static DelegateBridge __Hotfix0__ChooseNpc; // 0x38
	private static DelegateBridge __Hotfix0__CalculateNpcScore; // 0x40
	private static DelegateBridge __Hotfix0__CalculateDefaultStrategy; // 0x48
	private static DelegateBridge __Hotfix0__CalculateChooseWinStrategy; // 0x50
	private static DelegateBridge __Hotfix0__CalculateChooseOddStrategy; // 0x58
	private static DelegateBridge __Hotfix0__CalculateFollowStrategy; // 0x60
	private static DelegateBridge __Hotfix0__SetNpcChoiceResult; // 0x68
	private static DelegateBridge __Hotfix0__LogRoundNpcResult; // 0x70
	private static DelegateBridge __Hotfix0__SetTeamList; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x1dcaec8 VA: 0x75943e2ec8
	public Void Init(DouququGameMode gameMode) { }
	// RVA: 0x1dcb56c VA: 0x75943e356c
	public Void BeforeBetAppear() { }
	// RVA: 0x1dcbeb0 VA: 0x75943e3eb0
	public Void OnRoundEnd(RoundResult result) { }
	// RVA: 0x1dcc130 VA: 0x75943e4130
	public List`1 GetNpcList(Boolean isLeft) { }
	// RVA: 0x1dcc1b8 VA: 0x75943e41b8
	public Boolean TryGetSelectorInfo(Act5FunNpcSelector selector, out Single value) { }
	// RVA: 0x1dcb0bc VA: 0x75943e30bc
	private Void _ProcessNpcInfoData() { }
	// RVA: 0x1dcb340 VA: 0x75943e3340
	private Void _ProcessNpcSelectorData() { }
	// RVA: 0x1dcb5f4 VA: 0x75943e35f4
	private Void _ChooseNpc() { }
	// RVA: 0x1dcb900 VA: 0x75943e3900
	private Void _CalculateNpcScore() { }
	// RVA: 0x1dcc704 VA: 0x75943e4704
	private Act5FunNpcChoice _CalculateDefaultStrategy(Act5FunNpcData npcInfoData) { }
	// RVA: 0x1dcc264 VA: 0x75943e4264
	private Act5FunNpcChoice _CalculateChooseWinStrategy(String npcId) { }
	// RVA: 0x1dcc3bc VA: 0x75943e43bc
	private Act5FunNpcChoice _CalculateChooseOddStrategy(String npcId) { }
	// RVA: 0x1dcc4c8 VA: 0x75943e44c8
	private Act5FunNpcChoice _CalculateFollowStrategy(String npcId, Boolean isFollowMore) { }
	// RVA: 0x1dcbf30 VA: 0x75943e3f30
	private Void _SetNpcChoiceResult(RoundResult result) { }
	// RVA: 0x1dcc808 VA: 0x75943e4808
	private Void _LogRoundNpcResult() { }
	// RVA: 0x1dcbc20 VA: 0x75943e3c20
	private Void _SetTeamList() { }
	// RVA: 0x1dcca80 VA: 0x75943e4a80
	public Void .ctor() { }
	// RVA: 0x1dccc90 VA: 0x75943e4c90
	private Int32 <_ChooseNpc>b__17_0(String lhs, String rhs) { }
}
```