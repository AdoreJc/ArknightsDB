# ArchiveMusicModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedMusicId`

- `String homeMusicId`

- `Boolean isInit`


## Methods

- `Void LoadData(String, ActArchiveComponentData, ActArchiveInfo)`

- `AudioArchiveResItemData _getArchiveMusicResData(String)`

- `String GetDefaultItemID()`

- `Int32 GetSelectedIndex(String)`

- `Boolean IsCurrHomeTheme()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveMusicModel : IHotfixable
{
	public ListDict`2 musicItems; // 0x10
	public String selectedMusicId; // 0x18
	public String homeMusicId; // 0x20
	public Boolean isInit; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__getArchiveMusicResData; // 0x8
	private static DelegateBridge __Hotfix0_GetDefaultItemID; // 0x10
	private static DelegateBridge __Hotfix0_GetSelectedIndex; // 0x18
	private static DelegateBridge __Hotfix0_IsCurrHomeTheme; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x30615c4 VA: 0x75956795c4
	public Void LoadData(String archiveId, ActArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x3061b84 VA: 0x7595679b84
	private AudioArchiveResItemData _getArchiveMusicResData(String musicId) { }
	// RVA: 0x3061cb4 VA: 0x7595679cb4
	public String GetDefaultItemID() { }
	// RVA: 0x3061198 VA: 0x7595679198
	public Int32 GetSelectedIndex(String selectedItemId) { }
	// RVA: 0x3060e58 VA: 0x7595678e58
	public Boolean IsCurrHomeTheme() { }
	// RVA: 0x3061e6c VA: 0x7595679e6c
	public Void .ctor() { }
}
```