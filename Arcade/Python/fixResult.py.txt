def fixResult(result):
    def fix(x):
        return x / 10

    return map(fix, result)
