# DIYRoomTemplateDatabase

**Namespace:** `Torappu.Building.DIY`


## Fields

- `CachedAssetLoader <cachedAssetLoader>k__BackingField`


## Properties

- `CachedAssetLoader cachedAssetLoader`


## Methods

- `CachedAssetLoader get_cachedAssetLoader()`

- `Void set_cachedAssetLoader(CachedAssetLoader)`

- `Void QueryData(Predicate`1, Action`1)`

- `Void QueryDatas(Predicate`1, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYRoomTemplateDatabase : IDIYRoomTemplateProvider
{
	private const String DEFAULT_ROOM_PATH; // 0x0
	private CachedAssetLoader <cachedAssetLoader>k__BackingField; // 0x10

	public CachedAssetLoader cachedAssetLoader { get; set; }

	// RVA: 0x37ca47c VA: 0x7595de247c
	public CachedAssetLoader get_cachedAssetLoader() { }
	// RVA: 0x37ca484 VA: 0x7595de2484
	public Void set_cachedAssetLoader(CachedAssetLoader value) { }
	// RVA: 0x37ca48c VA: 0x7595de248c
	public Void QueryData(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37ca658 VA: 0x7595de2658
	public Void QueryDatas(Predicate`1 filter, Action`1 action) { }
	// RVA: 0x37ca7dc VA: 0x7595de27dc
	public Void .ctor() { }
}
```