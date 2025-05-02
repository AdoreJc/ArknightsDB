# BoundingBoxFollowerGraphic

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonGraphic skeletonGraphic`

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

- `Void HandleRebuild(SkeletonGraphic)`

- `Void Initialize(Boolean)`

- `Void AddCollidersForSkin(Skin, Int32, PolygonCollider2D[], Single, ref)`

- `Void OnDisable()`

- `Void ClearState()`

- `Void DisposeExcessCollidersAfter(Int32)`

- `Void LateUpdate()`

- `Void MatchAttachment(Attachment)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class BoundingBoxFollowerGraphic : MonoBehaviour
{
	internal static Boolean DebugMessages; // 0x0
	public SkeletonGraphic skeletonGraphic; // 0x18
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

	// RVA: 0x61fe214 VA: 0x7598816214
	public Slot get_Slot() { }
	// RVA: 0x61fe21c VA: 0x759881621c
	public BoundingBoxAttachment get_CurrentAttachment() { }
	// RVA: 0x61fe224 VA: 0x7598816224
	public String get_CurrentAttachmentName() { }
	// RVA: 0x61fe22c VA: 0x759881622c
	public PolygonCollider2D get_CurrentCollider() { }
	// RVA: 0x61fe234 VA: 0x7598816234
	public Boolean get_IsTrigger() { }
	// RVA: 0x61fe23c VA: 0x759881623c
	private Void Start() { }
	// RVA: 0x61fe82c VA: 0x759881682c
	private Void OnEnable() { }
	// RVA: 0x61febac VA: 0x7598816bac
	private Void HandleRebuild(SkeletonGraphic sr) { }
	// RVA: 0x61fe244 VA: 0x7598816244
	public Void Initialize(Boolean overwrite) { }
	// RVA: 0x61fef94 VA: 0x7598816f94
	private Void AddCollidersForSkin(Skin skin, Int32 slotIndex, PolygonCollider2D[] previousColliders, Single scale, ref Int32 collidersCount) { }
	// RVA: 0x61ff510 VA: 0x7598817510
	private Void OnDisable() { }
	// RVA: 0x61ff5ec VA: 0x75988175ec
	public Void ClearState() { }
	// RVA: 0x61ff420 VA: 0x7598817420
	private Void DisposeExcessCollidersAfter(Int32 requiredCount) { }
	// RVA: 0x61ff78c VA: 0x759881778c
	private Void LateUpdate() { }
	// RVA: 0x61ff7ac VA: 0x75988177ac
	private Void MatchAttachment(Attachment attachment) { }
	// RVA: 0x61ffb08 VA: 0x7598817b08
	public Void .ctor() { }
	// RVA: 0x61ffbe8 VA: 0x7598817be8
	private static Void .cctor() { }
}
```