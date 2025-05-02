# Act1VAutoChessEntryView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessEntryAnimView _entryAnimView`

- `Boolean m_isInited`

- `Int32 m_cachedFastModeSeq`

- `Coroutine m_tutorialCoroutine`

- `UIPageFinder m_pageFinder`

- `Act1VAutoChessEntryPage m_page`


## Methods

- `Void Init(Act1VAutoChessEntryPage)`

- `Void _InitIfNot()`

- `Void _EnsureSubViews()`

- `Void _EnsureSubViewAnims()`

- `Void _TryRefreshSubViews(Act1VAutoChessEntryViewModel)`

- `Void _TryStartTutorialCo(ShowType)`

- `IEnumerator _TutorialOnlyTryRaiseAVGSignal(ShowType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryView : DataBinder`1
{
	private List`1 _subViewHolders; // 0x20
	private Act1VAutoChessEntryAnimView _entryAnimView; // 0x28
	private Boolean m_isInited; // 0x30
	private Int32 m_cachedFastModeSeq; // 0x34
	private ListDict`2 m_subViewInfoDict; // 0x38
	private Coroutine m_tutorialCoroutine; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private Act1VAutoChessEntryPage m_page; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__EnsureSubViews; // 0x18
	private static DelegateBridge __Hotfix0__EnsureSubViewAnims; // 0x20
	private static DelegateBridge __Hotfix0__TryRefreshSubViews; // 0x28
	private static DelegateBridge __Hotfix0__TryStartTutorialCo; // 0x30
	private static DelegateBridge __Hotfix0__TutorialOnlyTryRaiseAVGSignal; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3337204 VA: 0x759594f204
	public Void Init(Act1VAutoChessEntryPage page) { }
	// RVA: 0x333d3a4 VA: 0x75959553a4
	public override Void OnValueChanged(Act1VAutoChessEntryProperty property) { }
	// RVA: 0x333d4a8 VA: 0x75959554a8
	private Void _InitIfNot() { }
	// RVA: 0x333d864 VA: 0x7595955864
	private Void _EnsureSubViews() { }
	// RVA: 0x333dbb8 VA: 0x7595955bb8
	private Void _EnsureSubViewAnims() { }
	// RVA: 0x333d534 VA: 0x7595955534
	private Void _TryRefreshSubViews(Act1VAutoChessEntryViewModel viewModel) { }
	// RVA: 0x333d750 VA: 0x7595955750
	private Void _TryStartTutorialCo(ShowType showType) { }
	// RVA: 0x333de7c VA: 0x7595955e7c
	private IEnumerator _TutorialOnlyTryRaiseAVGSignal(ShowType showType) { }
	// RVA: 0x333df68 VA: 0x7595955f68
	public Void .ctor() { }
}
```