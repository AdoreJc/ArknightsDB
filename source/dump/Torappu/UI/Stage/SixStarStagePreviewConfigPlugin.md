# SixStarStagePreviewConfigPlugin

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageViewModel m_stageModel`

- `IStageSelectHandler m_selectStageHandler`

- `StageSixStarInfo m_stageSixStarInfo`


## Methods

- `Void SetData(StageViewModel, IStageSelectHandler)`

- `Boolean CheckCanAutoBattle(Boolean)`

- `Boolean CheckCanPractice(Boolean)`

- `Boolean CheckCanContinuousBattle(Boolean)`

- `Int32 GetNoCostCnt(Int32)`

- `Boolean _CheckIfSixStarSelectBaseRune(StageSixStarInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarStagePreviewConfigPlugin : IPreviewConfigViewModelPlugin, IHotfixable
{
	private StageViewModel m_stageModel; // 0x10
	private IStageSelectHandler m_selectStageHandler; // 0x18
	private StageSixStarInfo m_stageSixStarInfo; // 0x20
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_CheckCanAutoBattle; // 0x8
	private static DelegateBridge __Hotfix0_CheckCanPractice; // 0x10
	private static DelegateBridge __Hotfix0_CheckCanContinuousBattle; // 0x18
	private static DelegateBridge __Hotfix0_GetNoCostCnt; // 0x20
	private static DelegateBridge __Hotfix0__CheckIfSixStarSelectBaseRune; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2f4be80 VA: 0x7595563e80
	public Void SetData(StageViewModel stageModel, IStageSelectHandler selectStageHandler) { }
	// RVA: 0x2f4bf80 VA: 0x7595563f80
	public Boolean CheckCanAutoBattle(Boolean canAutoBattle) { }
	// RVA: 0x2f4c0a4 VA: 0x75955640a4
	public Boolean CheckCanPractice(Boolean canPractice) { }
	// RVA: 0x2f4c138 VA: 0x7595564138
	public Boolean CheckCanContinuousBattle(Boolean canContinuousBattle) { }
	// RVA: 0x2f4c1cc VA: 0x75955641cc
	public Int32 GetNoCostCnt(Int32 noCostCnt) { }
	// RVA: 0x2f4c014 VA: 0x7595564014
	private Boolean _CheckIfSixStarSelectBaseRune(StageSixStarInfo stageSixStarInfo) { }
	// RVA: 0x2f4c260 VA: 0x7595564260
	public Void .ctor() { }
}
```