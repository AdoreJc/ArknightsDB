# TorappuAudioDB

**Namespace:** `Torappu.Audio.Middleware.Data`


## Methods

- `MusicData GetMusicByBankName(String)`

- `MusicData GetMusicById(String)`

- `BGMBank GetBgmBankByName(String)`

- `DuckingData GetDuckingDataByBankName(String)`

- `FadeStyleData GetFadeStyleDataByName(String)`

- `Void GetBanks(Dictionary`2)`

- `Void _TryAddBank(Dictionary`2, Bank)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Middleware.Data
public class TorappuAudioDB : ConstTable`2
{
	private Dictionary`2 m_srcBankToMusic; // 0x60
	private Dictionary`2 m_musicSearchTable; // 0x68
	private Dictionary`2 m_bgmBankTable; // 0x70
	private Dictionary`2 m_duckingDataTable; // 0x78
	private Dictionary`2 m_fadeStyleTable; // 0x80
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetMusicByBankName; // 0x8
	private static DelegateBridge __Hotfix0_GetMusicById; // 0x10
	private static DelegateBridge __Hotfix0_GetBgmBankByName; // 0x18
	private static DelegateBridge __Hotfix0_GetDuckingDataByBankName; // 0x20
	private static DelegateBridge __Hotfix0_GetFadeStyleDataByName; // 0x28
	private static DelegateBridge __Hotfix0_GetBanks; // 0x30
	private static DelegateBridge __Hotfix0__TryAddBank; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3ee34f0 VA: 0x75964fb4f0
	protected override Void OnInit() { }
	// RVA: 0x3ee3920 VA: 0x75964fb920
	public MusicData GetMusicByBankName(String bankName) { }
	// RVA: 0x3ee3a38 VA: 0x75964fba38
	public MusicData GetMusicById(String musicId) { }
	// RVA: 0x3ee3af8 VA: 0x75964fbaf8
	public BGMBank GetBgmBankByName(String bgmBankName) { }
	// RVA: 0x3ee3bc0 VA: 0x75964fbbc0
	public DuckingData GetDuckingDataByBankName(String bankName) { }
	// RVA: 0x3ee3c88 VA: 0x75964fbc88
	public FadeStyleData GetFadeStyleDataByName(String styleName) { }
	// RVA: 0x3edf73c VA: 0x75964f773c
	public Void GetBanks(Dictionary`2 banks) { }
	// RVA: 0x3ee3d50 VA: 0x75964fbd50
	private Void _TryAddBank(Dictionary`2 dict, Bank bank) { }
	// RVA: 0x3ee3efc VA: 0x75964fbefc
	public Void .ctor() { }
}
```