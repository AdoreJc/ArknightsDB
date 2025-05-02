# MedalDIYViewModel

**Namespace:** `Torappu.UI.Medal`


## Fields

- `String frameId`


## Methods

- `Void InitData(String)`

- `Void UpdateStatus(ICollection`1)`

- `DIYMedalModel GetMedalModel(String)`

- `Boolean TryGetTokenValidPos(String, out)`

- `Void ConfirmTokenPos(String, HexPoint)`

- `Void RemoveTokenPos(String)`

- `Void AdjustMedalList(ListDict`2)`

- `Void ResetAllTokens()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalDIYViewModel : IHotfixable
{
	public String frameId; // 0x10
	public Dictionary`2 medals; // 0x18
	public Dictionary`2 tokens; // 0x20
	public List`1 cardList; // 0x28
	private List`1 m_sharedIds; // 0x30
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetMedalModel; // 0x10
	private static DelegateBridge __Hotfix0_TryGetTokenValidPos; // 0x18
	private static DelegateBridge __Hotfix0_ConfirmTokenPos; // 0x20
	private static DelegateBridge __Hotfix0_RemoveTokenPos; // 0x28
	private static DelegateBridge __Hotfix0_AdjustMedalList; // 0x30
	private static DelegateBridge __Hotfix0_ResetAllTokens; // 0x38
	private static DelegateBridge __Hotfix0__MedalModelComparer; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x276267c VA: 0x7594d7a67c
	public Void InitData(String frameId) { }
	// RVA: 0x2762924 VA: 0x7594d7a924
	public Void UpdateStatus(ICollection`1 selectedMedalIds) { }
	// RVA: 0x2762f38 VA: 0x7594d7af38
	public DIYMedalModel GetMedalModel(String id) { }
	// RVA: 0x2762ff4 VA: 0x7594d7aff4
	public Boolean TryGetTokenValidPos(String medalId, out HexPoint validPos) { }
	// RVA: 0x27630c8 VA: 0x7594d7b0c8
	public Void ConfirmTokenPos(String medalId, HexPoint pos) { }
	// RVA: 0x2763188 VA: 0x7594d7b188
	public Void RemoveTokenPos(String medalId) { }
	// RVA: 0x276323c VA: 0x7594d7b23c
	public Void AdjustMedalList(ListDict`2 removedMedalLerps) { }
	// RVA: 0x27635c0 VA: 0x7594d7b5c0
	public Void ResetAllTokens() { }
	// RVA: 0x27636c8 VA: 0x7594d7b6c8
	private static Int32 _MedalModelComparer(DIYMedalModel lhs, DIYMedalModel rhs) { }
	// RVA: 0x27637b8 VA: 0x7594d7b7b8
	public Void .ctor() { }
}
```