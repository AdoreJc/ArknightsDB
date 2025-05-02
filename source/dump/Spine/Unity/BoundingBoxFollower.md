# BoundingBoxFollower

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonRenderer skeletonRenderer`

- `String slotName`

- `Boolean isTrigger`

- `Boolean clearStateOnDisable`

- `Slot slot`

- `BoundingBoxAttachment currentAttachment`

- `String currentAttachmentName`

- `PolygonCollider2D currentCollider`


## Properties

- `Slot Slot`

- `BoundingBoxAttachment CurrentAttachment`

- `String CurrentAttachmentName`

- `PolygonCollider2D CurrentCollider`

- `Boolean IsTrigger`


## Methods

- `Slot get_Slot()`

- `BoundingBoxAttachment get_CurrentAttachment()`

- `String get_CurrentAttachmentName()`

- `PolygonCollider2D get_CurrentCollider()`

- `Boolean get_IsTrigger()`

- `Void Start()`

- `Void OnEnable()`

- `Void HandleRebuild(SkeletonRenderer)`

- `Void Initialize(Boolean)`

- `Void AddCollidersForSkin(Skin, Int32, PolygonCollider2D[], ref)`

- `Void OnDisable()`

- `Void ClearState()`

- `Void DisposeExcessCollidersAfter(Int32)`

- `Void LateUpdate()`

- `Void MatchAttachment(Attachment)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class BoundingBoxFollower : MonoBehaviour
{
	internal static Boolean DebugMessages; // 0x0
	public SkeletonRenderer skeletonRenderer; // 0x18
	public String slotName; // 0x20
	public Boolean isTrigger; // 0x28
	public Boolean clearStateOnDisable; // 0x29
	private Slot slot; // 0x30
	private BoundingBoxAttachment currentAttachment; // 0x38
	private String currentAttachmentName; // 0x40
	private PolygonCollider2D currentCollider; // 0x48
	public readonly Dictionary`2 colliderTable; // 0x50
	public readonly Dictionary`2 nameTable; // 0x58

	public Slot Slot { get; }
	public BoundingBoxAttachment CurrentAttachment { get; }
	public String CurrentAttachmentName { get; }
	public PolygonCollider2D CurrentCollider { get; }
	public Boolean IsTrigger { get; }

	// RVA: 0x61fcf10 VA: 0x7598814f10
	public Slot get_Slot() { }
	// RVA: 0x61fcf18 VA: 0x7598814f18
	public BoundingBoxAttachment get_CurrentAttachment() { }
	// RVA: 0x61fcf20 VA: 0x7598814f20
	public String get_CurrentAttachmentName() { }
	// RVA: 0x61fcf28 VA: 0x7598814f28
	public PolygonCollider2D get_CurrentCollider() { }
	// RVA: 0x61fcf30 VA: 0x7598814f30
	public Boolean get_IsTrigger() { }
	// RVA: 0x61fcf38 VA: 0x7598814f38
	private Void Start() { }
	// RVA: 0x61fd45c VA: 0x759881545c
	private Void OnEnable() { }
	// RVA: 0x61fd568 VA: 0x7598815568
	private Void HandleRebuild(SkeletonRenderer sr) { }
	// RVA: 0x61fcf40 VA: 0x7598814f40
	public Void Initialize(Boolean overwrite) { }
	// RVA: 0x61fd570 VA: 0x7598815570
	private Void AddCollidersForSkin(Skin skin, Int32 slotIndex, PolygonCollider2D[] previousColliders, ref Int32 collidersCount) { }
	// RVA: 0x61fdaec VA: 0x7598815aec
	private Void OnDisable() { }
	// RVA: 0x61fdbcc VA: 0x7598815bcc
	public Void ClearState() { }
	// RVA: 0x61fd9fc VA: 0x75988159fc
	private Void DisposeExcessCollidersAfter(Int32 requiredCount) { }
	// RVA: 0x61fdd6c VA: 0x7598815d6c
	private Void LateUpdate() { }
	// RVA: 0x61fdd8c VA: 0x7598815d8c
	private Void MatchAttachment(Attachment attachment) { }
	// RVA: 0x61fe0e8 VA: 0x75988160e8
	public Void .ctor() { }
	// RVA: 0x61fe1c8 VA: 0x75988161c8
	private static Void .cctor() { }
}
```