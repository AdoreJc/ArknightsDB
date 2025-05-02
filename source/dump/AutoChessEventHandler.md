# AutoChessEventHandler

**Namespace:** ` `


## Methods

- `Void Init()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessEventHandler : IHotfixable
{
	private Dictionary`2 m_eventMap; // 0x10
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__OnTryRaiseTutorial; // 0x10
	private static DelegateBridge __Hotfix0__UpdateGameStatus; // 0x18
	private static DelegateBridge __Hotfix0__OnSpeedClick; // 0x20
	private static DelegateBridge __Hotfix0__OnNeedInterrupt; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private static AutoChessGameMode gameMode { get; }

	// RVA: 0x1c99c40 VA: 0x75942b1c40
	private static AutoChessGameMode get_gameMode() { }
	// RVA: 0x1c920b4 VA: 0x75942aa0b4
	public Void Init() { }
	// RVA: 0x1c99cc0 VA: 0x75942b1cc0
	private static Void _OnTryRaiseTutorial(Object arg) { }
	// RVA: 0x1c99d24 VA: 0x75942b1d24
	private static Void _UpdateGameStatus(Object arg) { }
	// RVA: 0x1c99db8 VA: 0x75942b1db8
	private static Void _OnSpeedClick(Object arg) { }
	// RVA: 0x1c9a04c VA: 0x75942b204c
	private static Void _OnNeedInterrupt(Object arg) { }
	// RVA: 0x1c90f88 VA: 0x75942a8f88
	public Void .ctor() { }
}
```