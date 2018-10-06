# szachy-casparow-vs-Copmuter
package szachy;

public class FinalKasparowAndDeepBlue {
	//Let do part of Chess final party Casparow vs Copmuter 1.0
	
	public static final int EMPTY = 0;
    public static final int B_PAWN = 1;
    public static final int B_ROOK = 2;
    public static final int B_BISHOP = 3;
    public static final int B_KNIGHT = 4;
    public static final int B_QUEEN = 5;
    public static final int B_KING = 6;

    public static final int W_PAWN = 7;
    public static final int W_ROOK = 8;
    public static final int W_BISHOP = 9;
    public static final int W_KNIGHT = 10;
    public static final int W_QUEEN = 11;
    public static final int W_KING = 12;
    
    private int[][] board = new int[8][8];

    public int[][] finalCasparowBoard() {
    		return new int[][] {
    
    		
    		{0, 0, 0, 0, 0, 0, 0, 0},
            {1, 1, 0, 0, 0, 0, 7, 0},
            {0, 0, 0, 0, 0, 0, 0, 0},
            {0, 0, 0, 0, 0, 0, 0, 0},
            {0, 4, 1, 0, 0, 10,0, 0},
            {0, 4, 0, 0, 8, 0, 7, 0},
            {0, 0, 0, 2, 0, 0, 0, 0},
            {0, 12,0, 0, 0, 0, 0, 0},
    };
    

}

	public int[][] getBoard() {
		return board;
	}

	public void setBoard(int[][] board) {
		this.board = board;
	}
}
