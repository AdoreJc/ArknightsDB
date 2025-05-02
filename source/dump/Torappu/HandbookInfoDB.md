# HandbookInfoDB

**Namespace:** `Torappu`


## Methods

- `Boolean TryGetName(String, out)`

- `HandbookStageTimeData GetNearestStageTimeData(Int64)`

- `Boolean CheckCharAvailable(String)`

- `Boolean CheckIfNpcHasAudio(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HandbookInfoDB : ConstTable`2
{
	private HashSet`1 m_audioNpcSet; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_TryGetName; // 0x8
	private static DelegateBridge __Hotfix0_GetNearestStageTimeData; // 0x10
	private static DelegateBridge __Hotfix0_CheckCharAvailable; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfNpcHasAudio; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x31f22d8 VA: 0x759580a2d8
	protected override Void OnInit() { }
	// RVA: 0x31f2460 VA: 0x759580a460
	public Boolean TryGetName(String key, out String name) { }
	// RVA: 0x31f2570 VA: 0x759580a570
	public HandbookStageTimeData GetNearestStageTimeData(Int64 timeStamp) { }
	// RVA: 0x31f26b8 VA: 0x759580a6b8
	public Boolean CheckCharAvailable(String charId) { }
	// RVA: 0x31f2858 VA: 0x759580a858
	public Boolean CheckIfNpcHasAudio(String npcId) { }
	// RVA: 0x31f291c VA: 0x759580a91c
	public Void .ctor() { }
}
```