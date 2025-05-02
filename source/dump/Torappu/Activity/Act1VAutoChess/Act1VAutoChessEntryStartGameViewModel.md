# Act1VAutoChessEntryStartGameViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `BandViewModel <selectedBand>k__BackingField`

- `Boolean <initShow>k__BackingField`

- `ShowState <showState>k__BackingField`

- `Boolean <blockingInteract>k__BackingField`


## Properties

- `BandViewModel selectedBand`

- `Boolean initShow`

- `ShowState showState`

- `Boolean blockingInteract`


## Methods

- `BandViewModel get_selectedBand()`

- `Void set_selectedBand(BandViewModel)`

- `Boolean get_initShow()`

- `Void set_initShow(Boolean)`

- `ShowState get_showState()`

- `Void set_showState(ShowState)`

- `Boolean get_blockingInteract()`

- `Void set_blockingInteract(Boolean)`

- `Void ResetStatus()`

- `Boolean SelectBand(String)`

- `Void SwitchShow()`

- `Void ReleaseBlocking()`

- `Void _LoadBands(String, ActivityAutoChessVerify1Data, PlayerAutoChessV1Activity)`

- `Void _LoadForces(ActivityAutoChessVerify1Data, PlayerAutoChessV1Activity)`

- `Void <>xLuaBaseProxy_LoadData(String, ActivityAutoChessVerify1Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryStartGameViewModel : Act1VAutoChessEntryBaseSubViewModel
{
	private readonly Dictionary`2 m_bandDict; // 0x28
	private readonly List`1 m_bandList; // 0x30
	private readonly List`1 m_forces; // 0x38
	private BandViewModel <selectedBand>k__BackingField; // 0x40
	private Boolean <initShow>k__BackingField; // 0x48
	private ShowState <showState>k__BackingField; // 0x4c
	private Boolean <blockingInteract>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_bands; // 0x0
	private static DelegateBridge __Hotfix0_get_forces; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedBand; // 0x10
	private static DelegateBridge __Hotfix0_set_selectedBand; // 0x18
	private static DelegateBridge __Hotfix0_get_initShow; // 0x20
	private static DelegateBridge __Hotfix0_set_initShow; // 0x28
	private static DelegateBridge __Hotfix0_get_showState; // 0x30
	private static DelegateBridge __Hotfix0_set_showState; // 0x38
	private static DelegateBridge __Hotfix0_get_blockingInteract; // 0x40
	private static DelegateBridge __Hotfix0_set_blockingInteract; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_ResetStatus; // 0x58
	private static DelegateBridge __Hotfix0_SelectBand; // 0x60
	private static DelegateBridge __Hotfix0_SwitchShow; // 0x68
	private static DelegateBridge __Hotfix0_ReleaseBlocking; // 0x70
	private static DelegateBridge __Hotfix0__LoadBands; // 0x78
	private static DelegateBridge __Hotfix0__LoadForces; // 0x80
	private static DelegateBridge __Hotfix0__BandComparison; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public List`1 bands { get; }
	public List`1 forces { get; }
	public BandViewModel selectedBand { get; set; }
	public Boolean initShow { get; set; }
	public ShowState showState { get; set; }
	public Boolean blockingInteract { get; set; }

	// RVA: 0x334cb40 VA: 0x7595964b40
	public List`1 get_bands() { }
	// RVA: 0x334bcc4 VA: 0x7595963cc4
	public List`1 get_forces() { }
	// RVA: 0x334ba64 VA: 0x7595963a64
	public BandViewModel get_selectedBand() { }
	// RVA: 0x3356364 VA: 0x759596e364
	private Void set_selectedBand(BandViewModel value) { }
	// RVA: 0x334c000 VA: 0x7595964000
	public Boolean get_initShow() { }
	// RVA: 0x33563e8 VA: 0x759596e3e8
	private Void set_initShow(Boolean value) { }
	// RVA: 0x334b9fc VA: 0x75959639fc
	public ShowState get_showState() { }
	// RVA: 0x3356468 VA: 0x759596e468
	private Void set_showState(ShowState value) { }
	// RVA: 0x334c30c VA: 0x759596430c
	public Boolean get_blockingInteract() { }
	// RVA: 0x33564e4 VA: 0x759596e4e4
	private Void set_blockingInteract(Boolean value) { }
	// RVA: 0x3356564 VA: 0x759596e564
	public override Void LoadData(String actId, ActivityAutoChessVerify1Data actData) { }
	// RVA: 0x3356f60 VA: 0x759596ef60
	public Void ResetStatus() { }
	// RVA: 0x3356ff0 VA: 0x759596eff0
	public Boolean SelectBand(String bandId) { }
	// RVA: 0x3357154 VA: 0x759596f154
	public Void SwitchShow() { }
	// RVA: 0x3357214 VA: 0x759596f214
	public Void ReleaseBlocking() { }
	// RVA: 0x3356668 VA: 0x759596e668
	private Void _LoadBands(String actId, ActivityAutoChessVerify1Data gameData, PlayerAutoChessV1Activity playerData) { }
	// RVA: 0x3356c40 VA: 0x759596ec40
	private Void _LoadForces(ActivityAutoChessVerify1Data gameData, PlayerAutoChessV1Activity playerData) { }
	// RVA: 0x33572f8 VA: 0x759596f2f8
	private static Int32 _BandComparison(BandViewModel x, BandViewModel y) { }
	// RVA: 0x33573b8 VA: 0x759596f3b8
	public Void .ctor() { }
	// RVA: 0x3357518 VA: 0x759596f518
	private Void <>xLuaBaseProxy_LoadData(String P0, ActivityAutoChessVerify1Data P1) { }
}
```