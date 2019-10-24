// calculating very large powers of a number eg 2^10**9

MOD = 1000000007
def fast_power(base, power):
    result = 1
    while power > 0:
        if power % 2 == 1:
            result = (result * base) % MOD
        power = power // 2
        base = (base * base) % MOD

    return result
