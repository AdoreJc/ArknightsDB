# CalcResult

**Namespace:** ` `


## Fields

- `DownloadPartEnum downloadPart`

- `Int64 baseDownloadSize`

- `Int64 extraDownloadSize`


## Methods

- `Void AddExtraVoiceRes(ABInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CalcResult : IHotfixable
{
	public DownloadPartEnum downloadPart; // 0x10
	public List`1 updateResList; // 0x18
	public Int64 baseDownloadSize; // 0x20
	public List`1 extraResList; // 0x28
	public Int64 extraDownloadSize; // 0x30
	public List`1 removeResList; // 0x38
	public Dictionary`2 extraVoiceRes; // 0x40
	public Dictionary`2 packInfo; // 0x48
	public HashSet`1 extraTypeHashSet; // 0x50
	public Dictionary`2 updatedNewABInfos; // 0x58
	private static DelegateBridge __Hotfix0_AddExtraVoiceRes; // 0x0
	private static DelegateBridge __Hotfix0_GenerateVoicePackItemInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x373bafc VA: 0x7595d53afc
	public Void AddExtraVoiceRes(ABInfo abInfo) { }
	// RVA: 0x373bce4 VA: 0x7595d53ce4
	public Dictionary`2 GenerateVoicePackItemInfo() { }
	// RVA: 0x373bed4 VA: 0x7595d53ed4
	public Void .ctor() { }
}
```