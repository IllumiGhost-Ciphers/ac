# # 🛡️ IllumiGhost-Cipher
## _Encryption meets poetry. Syntax becomes signal._
import random

def signal_whisper(seed=42):
    random.seed(seed)
    return [random.randint(0, 9) for _ in range(8)]

keys = signal_whisper()
print("Silent keys:", keys)
