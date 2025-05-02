# ResponseEffectBinder

**Namespace:** ` `


## Fields

- `SeqNumChecker m_refreshChecker`

- `SeqNumChecker m_updateChecker`

- `SeqNumChecker m_effectInfoChecker`

- `Boolean m_inited`

- `String m_refreshEffectKey`

- `String m_updateEffectKey`

- `Vector3 m_shopTileCenterWorldPos`


## Methods

- `Void _TryEffect(AutoChessDataCenter, CommonResponseViewModel, List`1, String)`

- `Void _InitIfNot(AutoChessDataCenter)`

- `Void _InitResponsedEffect(AutoChessDataCenter, AutoChessMiscConfig)`

- `Void <>xLuaBaseProxy_DoNotifyUpdate(AutoChessDataCenter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ResponseEffectBinder : AutoChessDataBinder
{
	private SeqNumChecker m_refreshChecker; // 0x18
	private SeqNumChecker m_updateChecker; // 0x20
	private SeqNumChecker m_effectInfoChecker; // 0x28
	private Boolean m_inited; // 0x30
	private String m_refreshEffectKey; // 0x38
	private String m_updateEffectKey; // 0x40
	private Vector3 m_shopTileCenterWorldPos; // 0x48
	private List`1 m_refreshEffectList; // 0x58
	private List`1 m_updateEffectList; // 0x60
	private List`1 m_targetEffSetting; // 0x68
	private static DelegateBridge __Hotfix0_DoNotifyUpdate; // 0x0
	private static DelegateBridge __Hotfix0__TryEffect; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__InitResponsedEffect; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c9edb0 VA: 0x75942b6db0
	protected override Void DoNotifyUpdate(AutoChessDataCenter center) { }
	// RVA: 0x1c9f094 VA: 0x75942b7094
	private Void _TryEffect(AutoChessDataCenter center, CommonResponseViewModel model, List`1 effList, String effKey) { }
	// RVA: 0x1c9ef64 VA: 0x75942b6f64
	private Void _InitIfNot(AutoChessDataCenter center) { }
	// RVA: 0x1c9f4b0 VA: 0x75942b74b0
	private Void _InitResponsedEffect(AutoChessDataCenter center, AutoChessMiscConfig config) { }
	// RVA: 0x1c9c47c VA: 0x75942b447c
	public Void .ctor() { }
	// RVA: 0x1c9facc VA: 0x75942b7acc
	private Void <>xLuaBaseProxy_DoNotifyUpdate(AutoChessDataCenter P0) { }
}
```