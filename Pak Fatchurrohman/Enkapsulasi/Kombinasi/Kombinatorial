public class Kombinatorial {
    private int n;
    private int k;
    private double kombinatorial;
    private int nk;
    private double kurang;

    public double getN() {
        return n;
    }

    public void setN(int n) {
        this.n = n;
    }

    public double getK() {
        return k;
    }

    public void setK(int k) {
        this.k = k;
    }

    public double getKombinatorial() {
        return kombinatorial;
    }

    public double getNk() {
        return nk;
    }

    public void setNk(int nk) {
        this.nk = nk;
    }

    public void hitung() {
        int hasil = 1;
        for (int i = 1; i <= n; i++) {
            hasil = hasil * i;
        }
        this.n = hasil;
    }

    public void hitung(int k) {
        int hasil = 1;
        for (int i = 1; i <= k; i++) {
            hasil *= i;
        }
        this.k = hasil;
    }

    public void ulangMin() {
        int hasil = 1;
        for (int i = 1; i <= nk; i++) {
            hasil *= i;
        }
        nk = hasil;
    }

    public void setKombinatorial(double n, double k, double nk) {
        double bagianBawah = nk * k;
        kombinatorial = n / bagianBawah;
    }

}
