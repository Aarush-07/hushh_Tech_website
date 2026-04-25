import { useNavigate } from "react-router-dom";

export default function NotFound() {
  const navigate = useNavigate();

  return (
    <div className="flex flex-col items-center justify-center h-screen bg-[#0d0d0d] text-white">
      <h1 className="text-6xl font-bold mb-4">404</h1>
      <p className="text-xl mb-6 opacity-70">
        You’ve wandered into the void...
      </p>

      <button
        onClick={() => navigate("/")}
        className="px-6 py-2 bg-white text-black rounded hover:bg-gray-300 transition"
      >
        Take me home
      </button>
    </div>
  );
}
