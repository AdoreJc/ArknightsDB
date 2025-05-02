# fiGraphMetadata

**Namespace:** `FullInspector`


## Fields

- `fiGraphMetadata _parentMetadata`

- `fiUnityObjectReference _targetObject`

- `String _accessPath`


## Properties

- `Object TargetObject`

- `String Path`


## Methods

- `Boolean ShouldSerialize()`

- `Void Serialize(out, out)`

- `Void AddSerializeData(List`1, List`1)`

- `Void Deserialize(String[], TPersistentData[])`

- `Void BeginCullZone()`

- `Void EndCullZone()`

- `Object get_TargetObject()`

- `String get_Path()`

- `Void RebuildAccessPath(String)`

- `Void SetChild(Int32, fiGraphMetadata)`

- `Void SetChild(String, fiGraphMetadata)`

- `fiGraphMetadataChild Enter(Int32)`

- `fiGraphMetadataChild Enter(String)`

- `T GetPersistentMetadata()`

- `T GetPersistentMetadata(out)`

- `T GetMetadata()`

- `T GetMetadata(out)`

- `T GetCommonMetadata(out)`

- `T GetInheritedMetadata()`

- `Boolean TryGetMetadata(out)`

- `Boolean TryGetInheritedMetadata(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class fiGraphMetadata
{
	private Dictionary`2 _precomputedData; // 0x10
	private CullableDictionary`3 _childrenInt; // 0x18
	private CullableDictionary`3 _childrenString; // 0x20
	private CullableDictionary`3 _metadata; // 0x28
	private fiGraphMetadata _parentMetadata; // 0x30
	private fiUnityObjectReference _targetObject; // 0x38
	private String _accessPath; // 0x40

	private Object TargetObject { get; }
	public String Path { get; }

	// RVA: 0x34ca988 VA: 0x7595ae2988
	public Boolean ShouldSerialize() { }
	// RVA: 0x VA: 0x0
	public Void Serialize(out String[] keys_, out TPersistentData[] values_) { }
	// RVA: 0x VA: 0x0
	private Void AddSerializeData(List`1 keys, List`1 values) { }
	// RVA: 0x VA: 0x0
	public Void Deserialize(String[] keys, TPersistentData[] values) { }
	// RVA: 0x34caa14 VA: 0x7595ae2a14
	public Void BeginCullZone() { }
	// RVA: 0x34caaac VA: 0x7595ae2aac
	public Void EndCullZone() { }
	// RVA: 0x34cab44 VA: 0x7595ae2b44
	private Object get_TargetObject() { }
	// RVA: 0x34cab88 VA: 0x7595ae2b88
	public String get_Path() { }
	// RVA: 0x34cab90 VA: 0x7595ae2b90
	public Void .ctor() { }
	// RVA: 0x34cab98 VA: 0x7595ae2b98
	public Void .ctor(fiUnityObjectReference targetObject) { }
	// RVA: 0x34cac08 VA: 0x7595ae2c08
	private Void .ctor(fiGraphMetadata parentMetadata, String accessKey) { }
	// RVA: 0x34caf84 VA: 0x7595ae2f84
	private Void RebuildAccessPath(String accessKey) { }
	// RVA: 0x34cb05c VA: 0x7595ae305c
	public Void SetChild(Int32 identifier, fiGraphMetadata metadata) { }
	// RVA: 0x34cb0e8 VA: 0x7595ae30e8
	public Void SetChild(String identifier, fiGraphMetadata metadata) { }
	// RVA: 0x VA: 0x0
	public static Void MigrateMetadata(fiGraphMetadata metadata, T[] previous, T[] updated) { }
	// RVA: 0x VA: 0x0
	private static List`1 ComputeNeededMigrations(fiGraphMetadata metadata, T[] previous, T[] updated) { }
	// RVA: 0x34cb160 VA: 0x7595ae3160
	public fiGraphMetadataChild Enter(Int32 childIdentifier) { }
	// RVA: 0x34cb25c VA: 0x7595ae325c
	public fiGraphMetadataChild Enter(String childIdentifier) { }
	// RVA: 0x VA: 0x0
	public T GetPersistentMetadata() { }
	// RVA: 0x VA: 0x0
	public T GetPersistentMetadata(out Boolean wasCreated) { }
	// RVA: 0x VA: 0x0
	public T GetMetadata() { }
	// RVA: 0x VA: 0x0
	public T GetMetadata(out Boolean wasCreated) { }
	// RVA: 0x VA: 0x0
	private T GetCommonMetadata(out Boolean wasCreated) { }
	// RVA: 0x VA: 0x0
	public T GetInheritedMetadata() { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetMetadata(out T metadata) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetInheritedMetadata(out T metadata) { }
}
```