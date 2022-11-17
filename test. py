import unittest
from logic import Board


class TestLogic(unittest.TestCase):

    def test_get_winner(self):
        board = Board()
        board.board = [
            ['X', None, 'O'],
            [None, 'X', None],
            [None, 'O', 'X'],
        ]
        self.assertEqual(board.get_winner(), 'X')

    # TODO: Test all functions from logic.py!

    def test_other_player(self):
        player = '1'
        self.assertEqual(Board.other_player(player), '0')
        player2 = '0'
        self.assertEqual(Board.other_player(player2), '1')

    def test_make_empty_board (self):
        empty_board = [
            [None, None, None],
            [None, None, None],
            [None, None, None],
        ]
        self.assertEqual(Board.make_empty_board(), empty_board)

if __name__ == '__main__':
    unittest.main()
