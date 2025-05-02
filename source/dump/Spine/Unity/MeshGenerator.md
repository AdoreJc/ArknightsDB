# MeshGenerator

**Namespace:** `Spine.Unity`


## Fields

- `Settings settings`

- `Vector2 meshBoundsMin`

- `Vector2 meshBoundsMax`

- `Single meshBoundsThickness`

- `Int32 submeshIndex`

- `SkeletonClipping clipper`


## Properties

- `Int32 VertexCount`

- `MeshGeneratorBuffers Buffers`


## Methods

- `Int32 get_VertexCount()`

- `MeshGeneratorBuffers get_Buffers()`

- `Void Begin()`

- `Void AddSubmesh(SubmeshInstruction, Boolean)`

- `Void BuildMesh(SkeletonRendererInstruction, Boolean)`

- `Void BuildMeshWithArrays(SkeletonRendererInstruction, Boolean)`

- `Void ScaleVertexData(Single)`

- `Void AddAttachmentTintBlack(Single, Single, Single, Single, Int32)`

- `Void FillVertexData(Mesh, Nullable`1, Boolean)`

- `Void FillLateVertexData(Mesh)`

- `Void FillTriangles(Mesh, Boolean)`

- `Void EnsureVertexCapacity(Int32, Boolean, Boolean, Boolean)`

- `Void TrimExcess()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class MeshGenerator
{
	public Settings settings; // 0x10
	private const Single BoundsMinDefault; // 0x0
	private const Single BoundsMaxDefault; // 0x0
	private readonly ExposedList`1 vertexBuffer; // 0x20
	private readonly ExposedList`1 uvBuffer; // 0x28
	private readonly ExposedList`1 colorBuffer; // 0x30
	private readonly ExposedList`1 submeshes; // 0x38
	private Vector2 meshBoundsMin; // 0x40
	private Vector2 meshBoundsMax; // 0x48
	private Single meshBoundsThickness; // 0x50
	private Int32 submeshIndex; // 0x54
	private SkeletonClipping clipper; // 0x58
	private Single[] tempVerts; // 0x60
	private Int32[] regionTriangles; // 0x68
	private Vector3[] normals; // 0x70
	private Vector4[] tangents; // 0x78
	private Vector2[] tempTanBuffer; // 0x80
	private ExposedList`1 uv2; // 0x88
	private ExposedList`1 uv3; // 0x90
	private static List`1 AttachmentVerts; // 0x0
	private static List`1 AttachmentUVs; // 0x8
	private static List`1 AttachmentColors32; // 0x10
	private static List`1 AttachmentIndices; // 0x18

	public Int32 VertexCount { get; }
	public MeshGeneratorBuffers Buffers { get; }

	// RVA: 0x62118ec VA: 0x75988298ec
	public Int32 get_VertexCount() { }
	// RVA: 0x6218134 VA: 0x7598830134
	public MeshGeneratorBuffers get_Buffers() { }
	// RVA: 0x620ee74 VA: 0x7598826e74
	public Void .ctor() { }
	// RVA: 0x62181ec VA: 0x75988301ec
	public static Void GenerateSingleSubmeshInstruction(SkeletonRendererInstruction instructionOutput, Skeleton skeleton, Material material) { }
	// RVA: 0x62186c8 VA: 0x75988306c8
	public static Boolean RequiresMultipleSubmeshesByDrawOrder(Skeleton skeleton) { }
	// RVA: 0x62188f8 VA: 0x75988308f8
	public static Void GenerateSkeletonRendererInstruction(SkeletonRendererInstruction instructionOutput, Skeleton skeleton, Dictionary`2 customSlotMaterials, List`1 separatorSlots, Boolean generateMeshOverride, Boolean immutableTriangles) { }
	// RVA: 0x6219144 VA: 0x7598831144
	public static Void TryReplaceMaterials(ExposedList`1 workingSubmeshInstructions, Dictionary`2 customMaterialOverride) { }
	// RVA: 0x620f9b8 VA: 0x75988279b8
	public Void Begin() { }
	// RVA: 0x620fa90 VA: 0x7598827a90
	public Void AddSubmesh(SubmeshInstruction instruction, Boolean updateTriangles) { }
	// RVA: 0x62193ec VA: 0x75988313ec
	public Void BuildMesh(SkeletonRendererInstruction instruction, Boolean updateTriangles) { }
	// RVA: 0x6210688 VA: 0x7598828688
	public Void BuildMeshWithArrays(SkeletonRendererInstruction instruction, Boolean updateTriangles) { }
	// RVA: 0x6219488 VA: 0x7598831488
	public Void ScaleVertexData(Single scale) { }
	// RVA: 0x621921c VA: 0x759883121c
	private Void AddAttachmentTintBlack(Single r2, Single g2, Single b2, Single a, Int32 vertexCount) { }
	// RVA: 0x6211908 VA: 0x7598829908
	public Void FillVertexData(Mesh mesh, Nullable`1 overrideBoundsCenter, Boolean reverseMesh) { }
	// RVA: 0x6212124 VA: 0x759882a124
	public Void FillLateVertexData(Mesh mesh) { }
	// RVA: 0x6211e34 VA: 0x7598829e34
	public Void FillTriangles(Mesh mesh, Boolean reverseMesh) { }
	// RVA: 0x6219884 VA: 0x7598831884
	public Void EnsureVertexCapacity(Int32 minimumVertexCount, Boolean inlcudeTintBlack, Boolean includeTangents, Boolean includeNormals) { }
	// RVA: 0x6219b1c VA: 0x7598831b1c
	public Void TrimExcess() { }
	// RVA: 0x621950c VA: 0x759883150c
	internal static Void SolveTangents2DEnsureSize(ref Vector4[] tangentBuffer, ref Vector2[] tempTanBuffer, Int32 vertexCount, Int32 vertexBufferLength) { }
	// RVA: 0x62195e4 VA: 0x75988315e4
	internal static Void SolveTangents2DTriangles(Vector2[] tempTanBuffer, Int32[] triangles, Int32 triangleCount, Vector3[] vertices, Vector2[] uvs, Int32 vertexCount) { }
	// RVA: 0x62197b8 VA: 0x75988317b8
	internal static Void SolveTangents2DBuffer(Vector4[] tangents, Vector2[] tempTanBuffer, Int32 vertexCount) { }
	// RVA: 0x6219c4c VA: 0x7598831c4c
	public static Void FillMeshLocal(Mesh mesh, RegionAttachment regionAttachment) { }
	// RVA: 0x621a618 VA: 0x7598832618
	public static Void FillMeshLocal(Mesh mesh, MeshAttachment meshAttachment, SkeletonData skeletonData) { }
	// RVA: 0x621af9c VA: 0x7598832f9c
	private static Void .cctor() { }
}
```