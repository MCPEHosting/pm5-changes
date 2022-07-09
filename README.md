# pm5-changes
PM5 changes

# Items/Blocks
- ItemFactory::getInstance()->get() & BlockFactory::getInstance()->get() was removed, use VanillaBlocks::BLOCK()/VanillaItems::ITEM()
- Item->getMeta() was removed
- Item->getId()/Block->getId() was renamed to Item->getTypeId()/Block->getTypeId()
- ItemIds and BlockLegacyIds was renamed to ItemTypeIds and BlockTypeIds
- To get a block as Item use VanillaBlocks::BLOCK()->asItem()
