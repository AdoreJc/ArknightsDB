# FocusCoreLogic

**Namespace:** ` `


## Fields

- `ViewInput m_inputInfo`

- `Tween m_focusTween`


## Methods

- `Void InitFocusInput(ViewInput)`

- `Void FocusToCharListChessCard(String, Int32, Action)`

- `Void FocusToSingleEditCharCard(String, Int32, Boolean, Action)`

- `Void FocusToPos(Single, Boolean, Action)`

- `Single GetPositionFromLevelAndColumnIndex(Int32, Single)`

- `Int32 GetLeftMostFocusChessInfo(out)`

- `Boolean _IsViewInputValid()`

- `Single _GetPositionInsideChild(Single)`

- `Single _CalculateVisibleColumnInsideChild(Bounds, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class FocusCoreLogic
{
	private ViewInput m_inputInfo; // 0x10
	private Tween m_focusTween; // 0x48


	// RVA: 0x3317230 VA: 0x759592f230
	public Void InitFocusInput(ViewInput input) { }
	// RVA: 0x3317258 VA: 0x759592f258
	public Void FocusToCharListChessCard(String chessId, Int32 level, Action onFocusFinished) { }
	// RVA: 0x3317958 VA: 0x759592f958
	public Void FocusToSingleEditCharCard(String chessId, Int32 level, Boolean fastMode, Action onFocusComplete) { }
	// RVA: 0x3317674 VA: 0x759592f674
	public Void FocusToPos(Single pos, Boolean fastMode, Action onFocusComplete) { }
	// RVA: 0x3317a60 VA: 0x759592fa60
	public Single GetPositionFromLevelAndColumnIndex(Int32 level, Single columnIndex) { }
	// RVA: 0x3317b30 VA: 0x759592fb30
	public Int32 GetLeftMostFocusChessInfo(out Single columnIndex) { }
	// RVA: 0x331748c VA: 0x759592f48c
	private Boolean _IsViewInputValid() { }
	// RVA: 0x3317aec VA: 0x759592faec
	private Single _GetPositionInsideChild(Single columnIndex) { }
	// RVA: 0x3317e8c VA: 0x759592fe8c
	private Single _CalculateVisibleColumnInsideChild(Bounds elementBounds, Single viewportMin) { }
	// RVA: 0x3317ffc VA: 0x759592fffc
	public Void .ctor() { }
}
```