# FunLiveUIBattleMenuSystemPanel

**Namespace:** `Torappu.Battle.FunLive`


## Fields

- `FunLiveUISystemMenuState m_state`


## Methods

- `Void Init(FunLiveUISystemMenuState)`

- `Void Show()`

- `Void CloseSystemMenuPanel()`

- `Void FinishGameDirectly()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.FunLive
public class FunLiveUIBattleMenuSystemPanel : MonoBehaviour, IHotfixable
{
	private FunLiveUISystemMenuState m_state; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_CloseSystemMenuPanel; // 0x10
	private static DelegateBridge __Hotfix0_FinishGameDirectly; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c5aa8c VA: 0x7594272a8c
	public Void Init(FunLiveUISystemMenuState state) { }
	// RVA: 0x1c5ac08 VA: 0x7594272c08
	public Void Show() { }
	// RVA: 0x1c5ac80 VA: 0x7594272c80
	public Void CloseSystemMenuPanel() { }
	// RVA: 0x1c5ad60 VA: 0x7594272d60
	public Void FinishGameDirectly() { }
	// RVA: 0x1c5ae40 VA: 0x7594272e40
	public Void .ctor() { }
}
```