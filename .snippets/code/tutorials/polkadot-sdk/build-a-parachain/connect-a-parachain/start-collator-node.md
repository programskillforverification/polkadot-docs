<div id="termynal" data-termynal>
  <span data-ty="input"><span class="file-path"></span>./target/release/parachain-template-node \
  --charlie \
  --collator \
  --force-authoring \
  --chain raw-parachain-chainspec.json \
  --base-path /tmp/charlie-parachain/ \
  --unsafe-force-node-key-generation \
  --port 40333 \
  --rpc-port 8844 \
  -- \
  --chain INSERT_RELAY_CHAIN_PATH/local-raw-spec.json \
  --port 30333 \
  --rpc-port 9946</span>
  <span data-ty>2024-09-10 16:26:30 [Parachain] PoV size { header: 0.21875kb, extrinsics: 3.6103515625kb, storage_proof: 3.150390625kb }</span>
  <span data-ty>2024-09-10 16:26:30 [Parachain] Compressed PoV size: 6.150390625kb</span>
  <span data-ty>2024-09-10 16:26:33 [Relaychain] 💤 Idle (2 peers), best: #1729 (0x3aa4…cb6b), finalized #1726 (0xff7a…4352), ⬇ 9.1kiB/s ⬆ 3.8kiB/s</span>
  <span data-ty="input"><span class="file-path"></span></span>
</div>